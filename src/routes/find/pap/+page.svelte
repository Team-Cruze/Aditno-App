<script>
  const navigateToFind = () => {
    window.location.href = "/find";
  };
</script>

<style>
  .container {
    width: 375px;
    height: 812px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    position: relative;
    background-color: #F3F4F6;
    font-family: 'Pretendard', sans-serif;
    margin: 0 auto;
    overflow: hidden;
    border-radius: 32px;
    margin: 40px auto 0; 
  }

  .image {
    width: 160px;
    height: 160px;
    margin-bottom: 20px;
    margin-top: auto; 
  }

  .message {
    font-size: 24px;
    color: #303030;
    margin-bottom: 40px;
    text-align: center;
    font-weight: 300;
  }

  .button {
    width: 310px;
    height: 50px;
    display: flex; 
    justify-content: center; 
    align-items: center; 
    background-color: #6184CA;
    color: white;
    text-align: center;
    font-size: 20px;
    font-weight: 600;
    border-radius: 8px;
    cursor: pointer;
    border: none; 
    margin-top: auto; 
    margin-bottom: 34px;
  }
</style>

<div class="container">
  <img src="/face.svg" alt="FaceImage" class="image" />
  <div class="message">50분 이내에<br> 물건을 찾아가주세요.</div>
  <button class="button" on:click={navigateToFind}>완료하기</button>
</div>
