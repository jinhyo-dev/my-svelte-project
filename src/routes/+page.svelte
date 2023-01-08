<script lang='ts'>
	const logo = new URL('../images/logo.png', import.meta.url).href;
</script>

<div class='logo-container' id='logo-container'>
	<img src={logo} alt='useLaboratory' loading='eager'>
</div>

<style lang='scss'>
    .logo-container {
				width: 100%;
        margin-left: auto;
        margin-right: auto;
				& img {
					width: 50%;
          display: block;
          margin-left: auto;
          margin-right: auto;
          animation: changeSize 3s ease forwards;
				}
    }

    @keyframes changeSize {
        0% {
						margin-top: 30vh;
        }
        100% {
            width: 25%;
						margin-top: 3vh;
        }
    }
</style>