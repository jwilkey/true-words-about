<template>
  <div>
    <div class="header">
      <p>TRUE WORDS</p>
    </div>

    <div class="content">
      <div class="slogan">
        YOU CAN STUDY THE BIBLE. HERE'S HOW.
      </div>
      <div>
        <h2>DESCRIPTION</h2>
        <p>True Words will help you to understand the Bible and apply it to your life. Choose a Bible passage that you want to study and then begin to engage with the text through immersive, guided activities. These activities will help you to understand what the passage says, discern what it means and finally to apply it specifically to your life.</p>
      </div>
      <div>
        <h2>LINKS</h2>
        <p>Application website: <a href="https://truewordsapp.com">https://truewordsapp.com</a></p>
        <p>iOS app: <a href="https://itunes.apple.com/us/app/true-words-bible-study/id1252109003?mt=8">iTunes app store</a></p>
      </div>
      <div class="media">
        <h2>IMAGE MEDIA</h2>
        <div class="media-item">
          <img src="/static/images/TrueWords_Brand.png" />
          <div class="divider"></div>
          <p class="media-title">Brand image</p>
        </div>
        <div class="media-item">
          <img src="/static/images/Icon600.png" />
          <div class="divider"></div>
          <p class="media-title">App icon</p>
        </div>
        <div class="media-item">
          <img src="/static/images/TrueWords_HD.jpg" />
          <div class="divider"></div>
          <p class="media-title">Hi Def Banner</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style lang="less" scoped>
h2 {
  font-size: 17px;
  font-weight: 400;
  padding-bottom: 5px;
  border-bottom: solid 1px #aaa;
  color: #444;
  margin-top: 20px;
}
p {
  color: #777;
  margin: 0;
  margin-bottom: 5px;
}

.header {
  text-align: center;
  padding: 10px;
  background-color: #fafafa;
  box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.3);
  display: table;
  width: 100%;
  p {
    display: table-cell;
    vertical-align: middle;
  }
}

.slogan {
  text-align: center;
  color: #777;
}
.content {
  padding: 10px;
}
.media {
  .media-item {
    border: solid 1px #444;
    border-radius: 4px;
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-bottom: 10px;
    height: 100px;
    img {
      max-height: 100%;
      max-width: 50%;
      padding: 8px;
    }
    .divider {
      height: 100%;
      width: 1px;
      background-color: #444;
    }
    p {
      padding: 15px;
    }
  }
}
</style>
