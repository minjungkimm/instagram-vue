<template>
  <aside class="main-aside">
    <div class="aside-my-profile">
      <div class="aside-my-profile-box">
        <img
          alt="sophia__min님의 프로필 사진"
          class="aside-my-profile-img"
          draggable="false"
          src="https://instagram.fjdo10-2.fna.fbcdn.net/v/t51.2885-19/44884218_345707102882519_2446069589734326272_n.jpg?_nc_ht=instagram.fjdo10-2.fna.fbcdn.net&amp;_nc_ohc=-dngjj927I8AX8F7YqT&amp;oh=9627cb043384056616a121d4f3894b0b&amp;oe=5EFFE60F&amp;ig_cache_key=YW5vbnltb3VzX3Byb2ZpbGVfcGlj.2"
        />
      </div>
      <div class="aside-my-profile-user-name-box">
        <span class="aside-my-profile-user-name">sophia_min</span>
      </div>
    </div>
    <div class="aside-recommend">
      <div class="aside-recommend-title-box">
        <div class="aside-recommend-title-box-depth">
          <span class="aside-recommend-title">
            회원님을 위한 추천
          </span>
        </div>
        <div class="aside-recommend-show-btn">
          <span class="aside-recommend-show-btn-text">
            모두 보기
          </span>
        </div>
      </div>
      <div class="aside-recommend-content-box">
        <div class="aside-recommend-content-box-depth">
          <RecommendUser />
          <RecommendUser />
          <RecommendUser />
          <RecommendUser />
          <RecommendUser />
        </div>
      </div>
    </div>
    <div class="aside-footer">
      <nav class="aside-footer-nav">
        <span class="aside-footer-nav-text">소개</span>
        <span class="aside-footer-nav-text">도움말</span>
        <span class="aside-footer-nav-text">홍보 센터</span>
        <span class="aside-footer-nav-text">API</span>
        <span class="aside-footer-nav-text">채용 정보</span>
        <span class="aside-footer-nav-text">개인정보처리방침</span>
        <span class="aside-footer-nav-text">약관</span>
        <span class="aside-footer-nav-text">위치</span>
        <span class="aside-footer-nav-text">인기 계정</span>
        <span class="aside-footer-nav-text">해시태그</span>
        <span class="aside-footer-nav-text">언어</span>
      </nav>
      <span class="aside-footer-text">© 2020 INSTAGRAM FROM FACEBOOK</span>
    </div>
  </aside>
</template>
<script>
import RecommendUser from '~/components/recommendUser.vue'
export default {
  components: {
    RecommendUser,
  },
}
</script>
