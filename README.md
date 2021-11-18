# jjangtaehoon1004.github.io
          
          {/* 로그인전화면 */}
          <Route path="/" element={<DefaultMain />}></Route>
          <Route path="/defaultsearch" element={<DefaultSearch />}></Route>

          {/* 로그인후화면 */}
          <Route path="/home" element={<Home />}></Route>

          {/* 그룹생성 
          1.치료구분 ~ 9.상세정보 */}
          <Route path="/groupadd" element={<GroupAdd />}></Route>

          {/* 그룹상세정보 */}
          <Route path="/groupinfo" element={<GroupInfo />}></Route>

          {/* 그룹참여신청 
          임시메뉴 >> 그룹참여신청:보호자, 그룹참여신청:치료사, 그룹초대:치료사, 그룹진행여부 */}
          <Route path="/groupjoin" element={<GroupJoin />}></Route>

          {/* 회원상세정보 
          치료사 소개, 치료사 상세, 담당 그룹, 치료후기 */}
          <Route path="/memberinfo" element={<MemberInfo />}></Route>

          {/* 치료일지 
          임시메뉴 >> 치료일지:치료사 , 치료사후기:보호자, 보호자후기:치료사 */}
          <Route path="/diary" element={<Diary />}></Route>

          {/* 나의정보 
          보호자 정보, 어린이 정보, 맞춤정보, 좋아요, 그룹정보, 참여신청*/}
          <Route path="/myinfo" element={<MyInfo />}></Route>

          {/* 로그인 */}
          <Route path="/signin" element={<SignInObj />}></Route>
          
          {/* 회원가입 */}
          <Route path="/signup" element={<SignUp />}></Route>
