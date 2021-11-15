# jjangtaehoon1004.github.io

          <Route path="/" element={<Home/>}></Route>
          
          <Route path="/groupadd"  element={<GroupAdd/>}></Route>
          버튼클릭 
          > 이전 / 다음 
          
          <Route path="/groupinfo"  element={<GroupInfo/>}></Route>
          메뉴클릭 
          >그룹목표
          >그룹상세
          >치료후기(123,123)
          
          <Route path="/memberinfo"  element={<MemberInfo/>}></Route>
          메뉴클릭
          치료사 소개
          치료사 상세
          담당 그룹
          치료후기(12)
          
          <Route path="/diary"  element={<Diary/>}></Route>
          <Route path="/myinfo"  element={<MyInfo/>}></Route>
          <Route path="/signin"  element={<SignInObj/>}></Route>
          <Route path="/signup"  element={<SignUp/>}></Route>
          <Route path="*" element={<div className='error'>에러 페이지</div>} />
