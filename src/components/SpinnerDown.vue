<template>
  <!--<svg class="spinner" viewBox="0 0 64 64"><g stroke-width="4" stroke-linecap="round"><line y1="17" y2="29" transform="translate(32,32) rotate(180)"><animate attributeName="stroke-opacity" dur="750ms" values="1;.85;.7;.65;.55;.45;.35;.25;.15;.1;0;1" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(210)"><animate attributeName="stroke-opacity" dur="750ms" values="0;1;.85;.7;.65;.55;.45;.35;.25;.15;.1;0" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(240)"><animate attributeName="stroke-opacity" dur="750ms" values=".1;0;1;.85;.7;.65;.55;.45;.35;.25;.15;.1" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(270)"><animate attributeName="stroke-opacity" dur="750ms" values=".15;.1;0;1;.85;.7;.65;.55;.45;.35;.25;.15" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(300)"><animate attributeName="stroke-opacity" dur="750ms" values=".25;.15;.1;0;1;.85;.7;.65;.55;.45;.35;.25" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(330)"><animate attributeName="stroke-opacity" dur="750ms" values=".35;.25;.15;.1;0;1;.85;.7;.65;.55;.45;.35" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(0)"><animate attributeName="stroke-opacity" dur="750ms" values=".45;.35;.25;.15;.1;0;1;.85;.7;.65;.55;.45" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(30)"><animate attributeName="stroke-opacity" dur="750ms" values=".55;.45;.35;.25;.15;.1;0;1;.85;.7;.65;.55" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(60)"><animate attributeName="stroke-opacity" dur="750ms" values=".65;.55;.45;.35;.25;.15;.1;0;1;.85;.7;.65" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(90)"><animate attributeName="stroke-opacity" dur="750ms" values=".7;.65;.55;.45;.35;.25;.15;.1;0;1;.85;.7" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(120)"><animate attributeName="stroke-opacity" dur="750ms" values=".85;.7;.65;.55;.45;.35;.25;.15;.1;0;1;.85" repeatCount="indefinite"></animate></line><line y1="17" y2="29" transform="translate(32,32) rotate(150)"><animate attributeName="stroke-opacity" dur="750ms" values="1;.85;.7;.65;.55;.45;.35;.25;.15;.1;0;1" repeatCount="indefinite"></animate></line></g></svg>-->
  <span class="loadmore">
    正在努力加载中...
    <svg viewBox="0 0 120 120" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
      <g id="circle" class="g-circles g-circles--v1">
        <circle id="12" transform="translate(35, 16.698730) rotate(-30) translate(-35, -16.698730) " cx="35" cy="16.6987298" r="10"></circle>
        <circle id="11" transform="translate(16.698730, 35) rotate(-60) translate(-16.698730, -35) " cx="16.6987298" cy="35" r="10"></circle>
        <circle id="10" transform="translate(10, 60) rotate(-90) translate(-10, -60) " cx="10" cy="60" r="10"></circle>
        <circle id="9" transform="translate(16.698730, 85) rotate(-120) translate(-16.698730, -85) " cx="16.6987298" cy="85" r="10"></circle>
        <circle id="8" transform="translate(35, 103.301270) rotate(-150) translate(-35, -103.301270) " cx="35" cy="103.30127" r="10"></circle>
        <circle id="7" cx="60" cy="110" r="10"></circle>
        <circle id="6" transform="translate(85, 103.301270) rotate(-30) translate(-85, -103.301270) " cx="85" cy="103.30127" r="10"></circle>
        <circle id="5" transform="translate(103.301270, 85) rotate(-60) translate(-103.301270, -85) " cx="103.30127" cy="85" r="10"></circle>
        <circle id="4" transform="translate(110, 60) rotate(-90) translate(-110, -60) " cx="110" cy="60" r="10"></circle>
        <circle id="3" transform="translate(103.301270, 35) rotate(-120) translate(-103.301270, -35) " cx="103.30127" cy="35" r="10"></circle>
        <circle id="2" transform="translate(85, 16.698730) rotate(-150) translate(-85, -16.698730) " cx="85" cy="16.6987298" r="10"></circle>
        <circle id="1" cx="60" cy="10" r="10"></circle>
      </g>
		  <use xlink:href="#circle" class="use"/>
	  </svg>
  </span>
</template>
<style scoped>
  svg{
    height:20px;
    width:20px;
    overflow:visible;
    vertical-align: middle;
    margin-top:-5px;
  }

  .g-circles{
    transform:scale(0.9) translate(7px, 7px);
  }

  circle{
    fill:#999;
    fill-opacity:0;
    animation:opacity 1.2s linear infinite;
  }
  circle:nth-child(12n + 1){
    animation-delay:-0.1s;
  }
  circle:nth-child(12n + 2){
    animation-delay:-0.2s;
  }
  circle:nth-child(12n + 3){
    animation-delay:-0.3s;
  }
  circle:nth-child(12n + 4){
    animation-delay:-0.4s;
  }
  circle:nth-child(12n + 5){
    animation-delay:-0.5s;
  }
  circle:nth-child(12n + 6){
    animation-delay:-0.6s;
  }
  circle:nth-child(12n + 7){
    animation-delay:-0.7s;
  }
  circle:nth-child(12n + 8){
    animation-delay:-0.8s;
  }
  circle:nth-child(12n + 9){
    animation-delay:-0.9s;
  }
  circle:nth-child(12n + 10){
    animation-delay:-1s;
  }
  circle:nth-child(12n + 11){
    animation-delay:-1.1s;
  }
  circle:nth-child(12n + 12){
    animation-delay:-1.2s;
  }
  @keyframes opacity{
    3%{
      fill-opacity:1;
    }

    75%{
      fill-opacity:0;
    }
  }
  @keyframes opacity-stroke{
    10%{
      stroke-opacity:1;
    }

    85%{
      stroke-opacity:0;
    }
  }
  @keyframes colors{
    0%{
      fill:#666;
    }

    10%{
      fill:gold;
    }

    75%{
      fill:crimson;
    }
  }
  @keyframes colors-stroke{
    0%{
      stroke:#999;
    }

    10%{
      stroke:gold;
    }

    75%{
      stroke:crimson;
    }
  }
  @keyframes transform{
    10%{
      -webkit-transform:scale(0.75);
      transform:scale(0.75);
    }
  }
</style>
