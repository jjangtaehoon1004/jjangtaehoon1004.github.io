# jjangtaehoon1004.github.io

          <Route path="/" element={<Home/>}></Route>
          <Route path="/main"  element={<Main/>}></Route>
          <Route path="/groupadd"  element={<GroupAdd/>}></Route>
          <Route path="/groupinfo"  element={<GroupInfo/>}></Route>
          <Route path="/memberinfo"  element={<MemberInfo/>}></Route>
          <Route path="/memberdetail"  element={<MemberDetail/>}></Route>
          <Route path="/membergroup"  element={<MemberGroup/>}></Route>
          <Route path="/memberboard"  element={<MemberBoard/>}></Route>
          <Route path="/diary"  element={<Diary/>}></Route>
          <Route path="/myinfo"  element={<MyInfo/>}></Route>
          <Route path="/signin"  element={<SignInObj/>}></Route>
          <Route path="/signup"  element={<SignUp/>}></Route>
          <Route path="/editor"  element={<Editor/>}></Route>
          <Route path="/test"  element={<Test/>}></Route>
          <Route path="/layout"  element={<Layout/>}></Route>
          <Route path="/slidertest"  element={<SliderTest/>}></Route>
          <Route path="*" element={<div className='error'>에러 페이지</div>} />
