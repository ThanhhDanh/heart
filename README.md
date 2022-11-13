# heart

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
    <title>Document</title>

    <style>
      html,
      body {
        height: 100%;
        padding: 0;
        margin: 0;
        background: rgba(0, 0, 0, 0.851);
        overflow: hidden;
      }
      canvas {
        position: absolute;
        width: 100%;
        height: 100%;
      }
      #pinkboard {
        animation: animate 1s infinite;
        z-index: 2;
      }

      .text {
        min-height: 100vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        color: red;
        text-shadow: 1px 1px 2px red, 0 0 1em blue, 0 0 0.2em blue;
        font-size: 180%;
        animation: animate 1s infinite;
      }

      @keyframes animate {
        0% {
          transform: scale(0.85, 0.85);
        }
        20% {
          transform: scale(0.85, 0.85);
        }
        40% {
          transform: scale(0.9, 0.9);
        }
        60% {
          transform: scale(0.85, 0.85);
        }
        80% {
          transform: scale(0.9, 0.9);
        }
        100% {
          transform: scale(0.85, 0.85);
        }
      }

      .container{
      margin: 0 auto;
      width: 50%;
      height: 300px;
      position: relative;
      text-align: center;
      opacity: 0.8;
      display:inline-flex;
      justify-content: center;
      align-items: center;
      }
      #img{
        border-radius: 50%;
        /* animation: anh 1.5s linear infinite alternate; */
        object-fit: contain;
      }
      #label{
        animation: doimau 1.5s linear infinite alternate ;
      }

      @keyframes doimau{
        0%{
          color: red;
          
        }
        50%{
          color: pink;
        
        }
        100%{
          color: aqua;
          
        }
      }
    </style>
  </head>
  <body>
    <div class="box">
      <canvas id="pinkboard"></canvas>
      <canvas id="pinkboardd"></canvas>
      <div class="text">
        <div class="container">
          <img class="slide" id="img" stt="0" onclick="changeImage" src="/imgaes/278531720_726140421722852_7925341685967779081_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="1" onclick="changeImage" src="/imgaes/279343142_1180715099504083_8614214721578379716_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="2" onclick="changeImage" src="" alt="">
          <img class="slide" id="img" style="display: none;" stt="3" onclick="changeImage" src="/imgaes/279574674_1018771648782724_6718610603234260725_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="4" onclick="changeImage" src="/imgaes/279591082_519105039755850_564365457520969807_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="5" onclick="changeImage" src="/imgaes/279705194_735592891212836_7059701948076588278_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="6" onclick="changeImage" src="/imgaes/279763086_345950307432798_3324360122623042576_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="7" onclick="changeImage" src="/imgaes/279789533_1772615636270296_6168842194688700686_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="8" onclick="changeImage" src="/imgaes/280035474_519231599650432_8315584909728628091_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="9" onclick="changeImage" src="/imgaes/280068179_7185054474898087_5515686584315218926_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="10" onclick="changeImage" src="/imgaes/280448435_375925354560544_4256987439150162084_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="11" onclick="changeImage" src="/imgaes/281777254_1152416508878578_2595398539808361455_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="12" onclick="changeImage" src="/imgaes/282054655_5506255952731906_8167004258989900804_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="13" onclick="changeImage" src="/imgaes/282385555_563440341818126_4596410095480853857_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="14" onclick="changeImage" src="/imgaes/283706320_589175639100793_5096987116122800839_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="15" onclick="changeImage" src="/imgaes/285052396_990825398284096_1023882945444832424_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="16" onclick="changeImage" src="/imgaes/287869134_566790458347913_2238402438937739784_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="17" onclick="changeImage" src="/imgaes/288633407_1177584773082927_3103657818374092349_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="18" onclick="changeImage" src="/imgaes/289557648_1160153981505423_8913052655070237875_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="19" onclick="changeImage" src="/imgaes/291785144_818501189138695_4833672954502069602_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="20" onclick="changeImage" src="/imgaes/298480759_3299687993689705_8979159706891247599_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="21" onclick="changeImage" src="/imgaes/298953789_1092976281648324_4387263422854251788_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="22" onclick="changeImage" src="/imgaes/299707895_2171238199711580_8501839497847568601_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="23" onclick="changeImage" src="/imgaes/302116188_785743892727818_5918113992026912535_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="24" onclick="changeImage" src="/imgaes/312806508_684466659670913_8061020990551410473_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="25" onclick="changeImage" src="/imgaes/313095514_473698971411789_6755823904786868414_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="26" onclick="changeImage" src="/imgaes/313095514_648553073342989_8477148154365878514_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="27" onclick="changeImage" src="/imgaes/313113852_523462756031901_6953281149868307463_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="28" onclick="changeImage" src="/imgaes/313341101_855053579271213_4053203317437291674_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="29" onclick="changeImage" src="/imgaes/313388834_1188243008569388_1945888732054506649_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="30" onclick="changeImage" src="/imgaes/314347972_1305567493511877_849811972772318983_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="31" onclick="changeImage" src="/imgaes/314375385_1321041601970634_660195810833369746_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="32" onclick="changeImage" src="/imgaes/314383609_693927981933286_8755967951880531756_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="33" onclick="changeImage" src="/imgaes/314398065_1852134625135663_4053817201980013256_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="34" onclick="changeImage" src="/imgaes/314437943_1872823649732100_8744064327571044533_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="35" onclick="changeImage" src="/imgaes/314474283_798928481441432_1840357547953395605_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="36" onclick="changeImage" src="/imgaes/314652729_515963730198853_6165551427937985231_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="37" onclick="changeImage" src="/imgaes/314748135_433566128956388_8202601085452006133_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="38" onclick="changeImage" src="/imgaes/314797461_821028555894010_6598885569926748393_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="39" onclick="changeImage" src="/imgaes/314895641_1555589398238942_2118826369763419686_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="40" onclick="changeImage" src="/imgaes/314897355_534225971476909_8820828144202353532_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="41" onclick="changeImage" src="/imgaes/314908868_821898548924714_992749794182414650_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="42" onclick="changeImage" src="/imgaes/314910056_351865680486464_2180596730202280787_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="43" onclick="changeImage" src="/imgaes/314913273_1085428165461121_8747011712929388320_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="44" onclick="changeImage" src="/imgaes/314921167_434839672191445_4491827313092330069_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="45" onclick="changeImage" src="/imgaes/314921173_1427584227769914_8953594520343297503_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="47" onclick="changeImage" src="/imgaes/314931698_665510435275143_8750755507840737323_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="48" onclick="changeImage" src="/imgaes/314989099_524340052887736_5077412133349975069_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="49" onclick="changeImage" src="/imgaes/314989632_456957893229844_6106900190554918664_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="50" onclick="changeImage" src="/imgaes/314991573_498902075605609_2004687777276453682_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="51" onclick="changeImage" src="/imgaes/315014415_1799593277082479_8733669361689529462_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="52" onclick="changeImage" src="/imgaes/315017437_728932702229827_787279318610491306_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="53" onclick="changeImage" src="/imgaes/315017445_1108991153146068_8435159631328233516_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="54" onclick="changeImage" src="/imgaes/315027749_981951765979647_1118208767338000607_n.jpg" alt="">
          <img class="slide" id="img" style="display: none;" stt="55" onclick="changeImage" src="/imgaes/315070622_829380471442155_6994317733906281052_n.jpg" alt="">
          <img src="/imgaes/315077826_817658442894715_7447244845933336066_n.jpg" alt="" class="slide" id="img" stt="56" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315080095_661939142303721_4417285208178971471_n.jpg" alt="" class="slide" id="img" stt="57" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315082111_2831117863686930_1518591267298964013_n.jpg" alt="" class="slide" id="img" stt="58" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315091660_682946599887431_5882368392624047626_n.jpg" alt="" class="slide" id="img" stt="59" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315097892_437579658549268_5459365577923673553_n.jpg" alt="" class="slide" id="img" stt="60" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315101954_507499338089149_6921312891602853283_n.jpg" alt="" class="slide" id="img" stt="61" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315103053_1462288357624901_4955666342381493097_n.jpg" alt="" class="slide" id="img" stt="62" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315105493_1330795944328846_3950124501415969140_n.jpg" alt="" class="slide" id="img" stt="63" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315105493_455943216664291_202776697960768129_n.jpg" alt="" class="slide" id="img" stt="64" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315105501_542549294369550_5378477196835117391_n.jpg" alt="" class="slide" id="img" stt="65" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315106199_688594495885572_3946048919779076227_n.jpg" alt="" class="slide" id="img" stt="66" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315109279_835698797745072_2460278304071542673_n.jpg" alt="" class="slide" id="img" stt="67" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315170947_860291194997335_7980195694469318864_n.jpg" alt="" class="slide" id="img" stt="68" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315187805_5871893062878516_8300237014612480415_n.jpg" alt="" class="slide" id="img" stt="69" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315188788_829540588364928_5806787908373776288_n.jpg" alt="" class="slide" id="img" stt="70" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315199126_1538336283276177_6206072957214759345_n.jpg" alt="" class="slide" id="img" stt="71" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315208361_1129759927657375_2660081392548134925_n.jpg" alt="" class="slide" id="img" stt="72" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315221265_704482117372741_5549533380083113355_n.jpg" alt="" class="slide" id="img" stt="73" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315244338_650962879976533_8347219536249976522_n.jpg" alt="" class="slide" id="img" stt="74" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315245183_450158397234421_299953565481545382_n.jpg" alt="" class="slide" id="img" stt="75" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315247502_427444682931378_3574020138878504557_n.jpg" alt="" class="slide" id="img" stt="76" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315275638_1556277258176607_2903826854049750777_n.jpg" alt="" class="slide" id="img" stt="77" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315302142_847905636413346_6858333532477508583_n.jpg" alt="" class="slide" id="img" stt="78" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315324294_693006775774747_675673757694076311_n.jpg" alt="" class="slide" id="img" stt="79" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315374639_665276401936525_1869051497795922772_n.jpg" alt="" class="slide" id="img" stt="80" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315436539_634044278413799_2850267759677392929_n.jpg" alt="" class="slide" id="img" stt="81" onclick="changeImage" style="display: none ;">
          <img src="/imgaes/315492528_425943316410051_7379856520568054418_n.jpg" alt="" class="slide" id="img" stt="82" onclick="changeImage" style="display: none ;">
          <div id="label">HEO MY
            <i class="fa-sharp fa-solid fa-heart"></i>
          </div>
        </div>
        
      </div>
    </div>

    <script>
      var settings = {
        particles: {
          length: 5000, // maximum amount of particles
          duration: 4, // particle duration in sec
          velocity: 80, // particle velocity in pixels/sec
          effect: -0.55, // play with this for a nice effect
          size: 10, // particle size in pixels
          alpha: 1,
        },
      };

      /*
       */
      (function () {
        var b = 0;
        var c = ["ms", "moz", "webkit", "o"];
        for (var a = 0; a < c.length && !window.requestAnimationFrame; ++a) {
          window.requestAnimationFrame = window[c[a] + "RequestAnimationFrame"];
          window.cancelAnimationFrame =
            window[c[a] + "CancelAnimationFrame"] ||
            window[c[a] + "CancelRequestAnimationFrame"];
        }
        if (!window.requestAnimationFrame) {
          window.requestAnimationFrame = function (h, e) {
            var d = new Date().getTime();
            var f = Math.max(0, 16 - (d - b));
            var g = window.setTimeout(function () {
              h(d + f);
            }, f);
            b = d + f;
            return g;
          };
        }
        if (!window.cancelAnimationFrame) {
          window.cancelAnimationFrame = function (d) {
            clearTimeout(d);
          };
        }
      })();
      /*
       * Point class
       */
      var Point = (function () {
        function Point(x, y) {
          this.x = typeof x !== "undefined" ? x : 0;
          this.y = typeof y !== "undefined" ? y : 0;
        }
        Point.prototype.clone = function () {
          return new Point(this.x, this.y);
        };
        Point.prototype.length = function (length) {
          if (typeof length == "undefined")
            return Math.sqrt(this.x * this.x + this.y * this.y);
          this.normalize();
          this.x *= length;
          this.y *= length;
          return this;
        };
        Point.prototype.normalize = function () {
          var length = this.length();
          this.x /= length;
          this.y /= length;
          return this;
        };
        return Point;
      })();

      /*
       * Particle class
       */
      var Particle = (function () {
        function Particle() {
          this.position = new Point();
          this.velocity = new Point();
          this.acceleration = new Point();
          this.alpha = new Point();
          this.age = 0;
        }
        Particle.prototype.initialize = function (x, y, dx, dy) {
          this.position.x = x;
          this.position.y = y;
          this.velocity.x = dx;
          this.velocity.y = dy;
          this.acceleration.x = dx * settings.particles.effect;
          this.acceleration.y = dy * settings.particles.effect;
          this.age = 0;
        };
        Particle.prototype.update = function (deltaTime) {
          this.position.x += this.velocity.x * deltaTime;
          this.position.y += this.velocity.y * deltaTime;
          this.velocity.x += this.acceleration.x * deltaTime;
          this.velocity.y += this.acceleration.y * deltaTime;
          this.age += deltaTime;
        };
        Particle.prototype.draw = function (context, image) {
          function ease(t) {
            return --t * t * t + 1;
          }
          var size = image.width * ease(this.age / settings.particles.duration);
          context.globalAlpha = 1 - this.age / settings.particles.duration;

          context.drawImage(
            image,
            this.position.x - size / 2,
            this.position.y - size / 2,
            size,
            size
          );
        };
        return Particle;
      })();
      /*
       * ParticlePool class
       */
      var ParticlePool = (function () {
        var particles,
          firstActive = 0,
          firstFree = 0,
          duration = settings.particles.duration;

        function ParticlePool(length) {
          // create and populate particle pool
          particles = new Array(length);
          for (var i = 0; i < particles.length; i++)
            particles[i] = new Particle();
        }
        ParticlePool.prototype.add = function (x, y, dx, dy) {
          particles[firstFree].initialize(x, y, dx, dy);

          // handle circular queue
          firstFree++;
          if (firstFree == particles.length) firstFree = 0;
          if (firstActive == firstFree) firstActive++;
          if (firstActive == particles.length) firstActive = 0;
        };
        ParticlePool.prototype.update = function (deltaTime) {
          var i;

          // update active particles
          if (firstActive < firstFree) {
            for (i = firstActive; i < firstFree; i++)
              particles[i].update(deltaTime);
          }
          if (firstFree < firstActive) {
            for (i = firstActive; i < particles.length; i++)
              particles[i].update(deltaTime);
            for (i = 0; i < firstFree; i++) particles[i].update(deltaTime);
          }

          // remove inactive particles
          while (
            particles[firstActive].age >= duration &&
            firstActive != firstFree
          ) {
            firstActive++;
            if (firstActive == particles.length) firstActive = 0;
          }
        };
        ParticlePool.prototype.draw = function (context, image) {
          // draw active particles
          if (firstActive < firstFree) {
            for (i = firstActive; i < firstFree; i++)
              particles[i].draw(context, image);
          }
          if (firstFree < firstActive) {
            for (i = firstActive; i < particles.length; i++)
              particles[i].draw(context, image);
            for (i = 0; i < firstFree; i++) particles[i].draw(context, image);
          }
        };
        return ParticlePool;
      })();
      /*
       * Putting it all together
       */
      (function (canvas) {
        var context = canvas.getContext("2d"),
          particles = new ParticlePool(settings.particles.length),
          particleRate =
            settings.particles.length / settings.particles.duration, // particles/sec
          time;

        // get point on heart with -PI <= t <= PI
        function pointOnHeart(t) {
          return new Point(
            160 * Math.pow(Math.sin(t), 3),
            130 * Math.cos(t) -
              50 * Math.cos(2 * t) -
              20 * Math.cos(3 * t) -
              10 * Math.cos(4 * t) +
              25
          );
        }

        // creating the particle image using a dummy canvas

        var image = (function () {
          var canvas = document.createElement("canvas"),
            context = canvas.getContext("2d");
          canvas.width = settings.particles.size;
          canvas.height = settings.particles.size;
          // helper function to create the path
          function to(t) {
            var point = pointOnHeart(t);
            point.x =
              settings.particles.size / 2 +
              (point.x * settings.particles.size) / 350;
            point.y =
              settings.particles.size / 2 -
              (point.y * settings.particles.size) / 350;
            return point;
          }
          // create the path
          context.beginPath();
          var t = -Math.PI;
          var point = to(t);
          var color = ["#f20000", "#fff"];
          while (t < Math.PI) {
            t += 0.01; // baby steps!
            point = to(t);
            w = Math.floor(Math.random() * (2.0 - -5.0)) + -5.0;
            context.fillRect(
              point.x,
              point.y,
              canvas.width + w,
              canvas.height + w
            );
            context.fillStyle = "red";
            // context.fillStyle = color[Math.floor(Math.random() * 2)];
          }

          context.closePath();
          // create the fill

          context.fill();
          // create the image
          var image = new Image();
          image.src = canvas.toDataURL();
          return image;
        })();
        // render that thing!
        function render() {
          // next animation frame
          requestAnimationFrame(render);

          // update time
          var newTime = new Date().getTime() / 1000,
            deltaTime = newTime - (time || newTime);
          time = newTime;

          // clear canvas
          context.clearRect(0, 0, canvas.width, canvas.height);

          // create new particles
          var amount = particleRate * deltaTime;
          for (var i = 0; i < amount; i++) {
            var pos = pointOnHeart(Math.PI - 2 * Math.PI * Math.random());
            var dir = pos.clone().length(settings.particles.velocity);
            particles.add(
              canvas.width / 2 + pos.x,
              canvas.height / 2 - pos.y,
              dir.x,
              -dir.y
            );
          }

          // update and draw particles
          particles.update(deltaTime);

          particles.draw(context, image);
        }

        // handle (re-)sizing of the canvas
        function onResize() {
          canvas.width = canvas.clientWidth;
          canvas.height = canvas.clientHeight;
        }
        window.onresize = onResize;

        // delay rendering bootstrap
        setTimeout(function () {
          onResize();
          render();
        }, 10);
      })(document.getElementById("pinkboard"));
    </script>

    <script>
      var settings1 = {
        particles: {
          length: 500, // maximum amount of particles

          duration: 2, // particle duration in sec

          velocity: 120, // particle velocity in pixels/sec

          effect: -0.75, // play with this for a nice effect

          size: 30, // particle size in pixels
        },
      };

      /*
    
    * RequestAnimationFrame polyfill by Erik Möller
    
    */

      // (function () {
      //   var b = 0;
      //   var c = ["ms", "moz", "webkit", "o"];
      //   for (var a = 0; a < c.length && !window.requestAnimationFrame; ++a) {
      //     window.requestAnimationFrame = window[c[a] + "RequestAnimationFrame"];
      //     window.cancelAnimationFrame =
      //       window[c[a] + "CancelAnimationFrame"] ||
      //       window[c[a] + "CancelRequestAnimationFrame"];
      //   }
      //   if (!window.requestAnimationFrame) {
      //     window.requestAnimationFrame = function (h, e) {
      //       var d = new Date().getTime();
      //       var f = Math.max(0, 16 - (d - b));
      //       var g = window.setTimeout(function () {
      //         h(d + f);
      //       }, f);
      //       b = d + f;
      //       return g;
      //     };
      //   }
      //   if (!window.cancelAnimationFrame) {
      //     window.cancelAnimationFrame = function (d) {
      //       clearTimeout(d);
      //     };
      //   }
      // })();

      /*
    
    * Point class
    
    */

      var Point = (function () {
        function Point(x, y) {
          this.x = typeof x !== "undefined" ? x : 0;

          this.y = typeof y !== "undefined" ? y : 0;
        }

        Point.prototype.clone = function () {
          return new Point(this.x, this.y);
        };

        Point.prototype.length = function (length) {
          if (typeof length == "undefined")
            return Math.sqrt(this.x * this.x + this.y * this.y);

          this.normalize();

          this.x *= length;

          this.y *= length;

          return this;
        };

        Point.prototype.normalize = function () {
          var length = this.length();

          this.x /= length;

          this.y /= length;

          return this;
        };

        return Point;
      })();

      /*
    
    * Particle class
    
    */

      var Particle = (function () {
        function Particle() {
          this.position = new Point();

          this.velocity = new Point();

          this.acceleration = new Point();

          this.age = 0;
        }

        Particle.prototype.initialize = function (x, y, dx, dy) {
          this.position.x = x;

          this.position.y = y;

          this.velocity.x = dx;

          this.velocity.y = dy;

          this.acceleration.x = dx * settings1.particles.effect;

          this.acceleration.y = dy * settings1.particles.effect;

          this.age = 0;
        };

        Particle.prototype.update = function (deltaTime) {
          this.position.x += this.velocity.x * deltaTime;

          this.position.y += this.velocity.y * deltaTime;

          this.velocity.x += this.acceleration.x * deltaTime;

          this.velocity.y += this.acceleration.y * deltaTime;

          this.age += deltaTime;
        };

        Particle.prototype.draw = function (context, image) {
          function ease(t) {
            return --t * t * t + 1;
          }

          var size =
            image.width * ease(this.age / settings1.particles.duration);

          context.globalAlpha = 1 - this.age / settings1.particles.duration;

          context.drawImage(
            image,
            this.position.x - size / 2,
            this.position.y - size / 2,
            size,
            size
          );
        };

        return Particle;
      })();

      /*
    
    * ParticlePool class
    
    */

      var ParticlePool = (function () {
        var particles,
          firstActive = 0,
          firstFree = 0,
          duration = settings1.particles.duration;

        function ParticlePool(length) {
          // create and populate particle pool

          particles = new Array(length);

          for (var i = 0; i < particles.length; i++)
            particles[i] = new Particle();
        }

        ParticlePool.prototype.add = function (x, y, dx, dy) {
          particles[firstFree].initialize(x, y, dx, dy);

          // handle circular queue

          firstFree++;

          if (firstFree == particles.length) firstFree = 0;

          if (firstActive == firstFree) firstActive++;

          if (firstActive == particles.length) firstActive = 0;
        };

        ParticlePool.prototype.update = function (deltaTime) {
          var i;

          // update active particles

          if (firstActive < firstFree) {
            for (i = firstActive; i < firstFree; i++)
              particles[i].update(deltaTime);
          }

          if (firstFree < firstActive) {
            for (i = firstActive; i < particles.length; i++)
              particles[i].update(deltaTime);

            for (i = 0; i < firstFree; i++) particles[i].update(deltaTime);
          }

          // remove inactive particles

          while (
            particles[firstActive].age >= duration &&
            firstActive != firstFree
          ) {
            firstActive++;

            if (firstActive == particles.length) firstActive = 0;
          }
        };

        ParticlePool.prototype.draw = function (context, image) {
          // draw active particles

          if (firstActive < firstFree) {
            for (i = firstActive; i < firstFree; i++)
              particles[i].draw(context, image);
          }

          if (firstFree < firstActive) {
            for (i = firstActive; i < particles.length; i++)
              particles[i].draw(context, image);

            for (i = 0; i < firstFree; i++) particles[i].draw(context, image);
          }
        };

        return ParticlePool;
      })();

      /*
    
    * Putting it all together
    
    */

      (function (canvas) {
        var context = canvas.getContext("2d"),
          particles = new ParticlePool(settings1.particles.length),
          particleRate =
            settings1.particles.length / settings1.particles.duration, // particles/sec
          time;

        // get point on heart with -PI <= t <= PI

        function pointOnHeart(t) {
          return new Point(
            160 * Math.pow(Math.sin(t), 3),

            130 * Math.cos(t) -
              50 * Math.cos(2 * t) -
              20 * Math.cos(3 * t) -
              10 * Math.cos(4 * t) +
              25
          );
        }

        // creating the particle image using a dummy canvas

        var image = (function () {
          var canvas = document.createElement("canvas"),
            context = canvas.getContext("2d");

          canvas.width = settings1.particles.size;

          canvas.height = settings1.particles.size;

          // helper function to create the path

          function to(t) {
            var point = pointOnHeart(t);

            point.x =
              settings1.particles.size / 2 +
              (point.x * settings1.particles.size) / 350;

            point.y =
              settings1.particles.size / 2 -
              (point.y * settings1.particles.size) / 350;

            return point;
          }

          // create the path

          context.beginPath();

          var t = -Math.PI;

          var point = to(t);

          context.moveTo(point.x, point.y);

          while (t < Math.PI) {
            t += 0.01; // baby steps!

            point = to(t);

            context.lineTo(point.x, point.y);
          }

          context.closePath();

          // create the fill

          context.fillStyle = "#ee5253";

          context.fill();

          // create the image

          var image = new Image();

          image.src = canvas.toDataURL();

          return image;
        })();

        // render that thing!

        function render() {
          // next animation frame

          requestAnimationFrame(render);

          // update time

          var newTime = new Date().getTime() / 1000,
            deltaTime = newTime - (time || newTime);

          time = newTime;

          // clear canvas

          context.clearRect(0, 0, canvas.width, canvas.height);

          // create new particles

          var amount = particleRate * deltaTime;

          for (var i = 0; i < amount; i++) {
            var pos = pointOnHeart(Math.PI - 2 * Math.PI * Math.random());

            var dir = pos.clone().length(settings1.particles.velocity);

            particles.add(
              canvas.width / 2 + pos.x,
              canvas.height / 2 - pos.y,
              dir.x,
              -dir.y
            );
          }

          // update and draw particles

          particles.update(deltaTime);

          particles.draw(context, image);
        }

        // handle (re-)sizing of the canvas

        function onResize() {
          canvas.width = canvas.clientWidth;

          canvas.height = canvas.clientHeight;
        }

        window.onresize = onResize;

        // delay rendering bootstrap

        setTimeout(function () {
          onResize();

          render();
        }, 10);
      })(document.getElementById("pinkboardd"));
    </script>
    <script>
        var index=1;
        changeImage=function(){
            var imgs=[ "/imgaes/278531720_726140421722852_7925341685967779081_n.jpg"
  ,"/imgaes/279343142_1180715099504083_8614214721578379716_n.jpg"
  ,"/imgaes/279574674_1018771648782724_6718610603234260725_n.jpg"
  ,"/imgaes/279591082_519105039755850_564365457520969807_n.jpg"
  ,"/imgaes/279705194_735592891212836_7059701948076588278_n.jpg"
  ,"/imgaes/279763086_345950307432798_3324360122623042576_n.jpg"
  ,"/imgaes/279789533_1772615636270296_6168842194688700686_n.jpg"
  ,"/imgaes/280035474_519231599650432_8315584909728628091_n.jpg"
  ,"/imgaes/280068179_7185054474898087_5515686584315218926_n.jpg"
  ,"/imgaes/280448435_375925354560544_4256987439150162084_n.jpg"
  ,"/imgaes/281777254_1152416508878578_2595398539808361455_n.jpg"
  ,"/imgaes/282054655_5506255952731906_8167004258989900804_n.jpg"
  ,"/imgaes/282385555_563440341818126_4596410095480853857_n.jpg"
  ,"/imgaes/283706320_589175639100793_5096987116122800839_n.jpg"
  ,"/imgaes/285052396_990825398284096_1023882945444832424_n.jpg"
  ,"/imgaes/287869134_566790458347913_2238402438937739784_n.jpg"
  ,"/imgaes/288633407_1177584773082927_3103657818374092349_n.jpg"
  ,"/imgaes/289557648_1160153981505423_8913052655070237875_n.jpg"
  ,"/imgaes/291785144_818501189138695_4833672954502069602_n.jpg"
  ,"/imgaes/298480759_3299687993689705_8979159706891247599_n.jpg"
  ,"/imgaes/298953789_1092976281648324_4387263422854251788_n.jpg"
  ,"/imgaes/299707895_2171238199711580_8501839497847568601_n.jpg"
  ,"/imgaes/302116188_785743892727818_5918113992026912535_n.jpg"
  ,"/imgaes/312806508_684466659670913_8061020990551410473_n.jpg"
  ,"/imgaes/313095514_473698971411789_6755823904786868414_n.jpg"
  ,"/imgaes/313095514_648553073342989_8477148154365878514_n.jpg"
  ,"/imgaes/313113852_523462756031901_6953281149868307463_n.jpg"
  ,"/imgaes/313341101_855053579271213_4053203317437291674_n.jpg"
  ,"/imgaes/313388834_1188243008569388_1945888732054506649_n.jpg"
  ,"/imgaes/314347972_1305567493511877_849811972772318983_n.jpg"
  ,"/imgaes/314375385_1321041601970634_660195810833369746_n.jpg"
  ,"/imgaes/314383609_693927981933286_8755967951880531756_n.jpg"
  ,"/imgaes/314398065_1852134625135663_4053817201980013256_n.jpg"
  ,"/imgaes/314437943_1872823649732100_8744064327571044533_n.jpg"
  ,"/imgaes/314474283_798928481441432_1840357547953395605_n.jpg"
  ,"/imgaes/314652729_515963730198853_6165551427937985231_n.jpg"
  ,"/imgaes/314748135_433566128956388_8202601085452006133_n.jpg"
  ,"/imgaes/314797461_821028555894010_6598885569926748393_n.jpg"
  ,"/imgaes/314895641_1555589398238942_2118826369763419686_n.jpg"
  ,"/imgaes/314897355_534225971476909_8820828144202353532_n.jpg"
  ,"/imgaes/314908868_821898548924714_992749794182414650_n.jpg"
  ,"/imgaes/314910056_351865680486464_2180596730202280787_n.jpg"
  ,"/imgaes/314913273_1085428165461121_8747011712929388320_n.jpg"
  ,"/imgaes/314921167_434839672191445_4491827313092330069_n.jpg"
  ,"/imgaes/314921173_1427584227769914_8953594520343297503_n.jpg"
  ,"/imgaes/314931698_665510435275143_8750755507840737323_n.jpg"
  ,"/imgaes/314989099_524340052887736_5077412133349975069_n.jpg"
  ,"/imgaes/314989632_456957893229844_6106900190554918664_n.jpg"
  ,"/imgaes/314991573_498902075605609_2004687777276453682_n.jpg"
  ,"/imgaes/315014415_1799593277082479_8733669361689529462_n.jpg"
  ,"/imgaes/315017437_728932702229827_787279318610491306_n.jpg"
  ,"/imgaes/315017445_1108991153146068_8435159631328233516_n.jpg"
  ,"/imgaes/315027749_981951765979647_1118208767338000607_n.jpg"
  ,"/imgaes/315070622_829380471442155_6994317733906281052_n.jpg"
  ,"/imgaes/315077826_817658442894715_7447244845933336066_n.jpg"
  ,"/imgaes/315080095_661939142303721_4417285208178971471_n.jpg"
  ,"/imgaes/315082111_2831117863686930_1518591267298964013_n.jpg"
  ,"/imgaes/315091660_682946599887431_5882368392624047626_n.jpg"
  ,"/imgaes/315097892_437579658549268_5459365577923673553_n.jpg"
  ,"/imgaes/315101954_507499338089149_6921312891602853283_n.jpg"
  ,"/imgaes/315103053_1462288357624901_4955666342381493097_n.jpg"
  ,"/imgaes/315105493_1330795944328846_3950124501415969140_n.jpg"
  ,"/imgaes/315105493_455943216664291_202776697960768129_n.jpg"
  ,"/imgaes/315105501_542549294369550_5378477196835117391_n.jpg"
  ,"/imgaes/315106199_688594495885572_3946048919779076227_n.jpg"
  ,"/imgaes/315109279_835698797745072_2460278304071542673_n.jpg"
  ,"/imgaes/315170947_860291194997335_7980195694469318864_n.jpg"
  ,"/imgaes/315187805_5871893062878516_8300237014612480415_n.jpg"
  ,"/imgaes/315188788_829540588364928_5806787908373776288_n.jpg"
  ,"/imgaes/315199126_1538336283276177_6206072957214759345_n.jpg"
  ,"/imgaes/315208361_1129759927657375_2660081392548134925_n.jpg"
  ,"/imgaes/315221265_704482117372741_5549533380083113355_n.jpg"
  ,"/imgaes/315244338_650962879976533_8347219536249976522_n.jpg"
  ,"/imgaes/315245183_450158397234421_299953565481545382_n.jpg"
  ,"/imgaes/315247502_427444682931378_3574020138878504557_n.jpg"
  ,"/imgaes/315275638_1556277258176607_2903826854049750777_n.jpg"
  ,"/imgaes/315302142_847905636413346_6858333532477508583_n.jpg"
  ,"/imgaes/315324294_693006775774747_675673757694076311_n.jpg"
  ,"/imgaes/315374639_665276401936525_1869051497795922772_n.jpg"
  ,"/imgaes/315436539_634044278413799_2850267759677392929_n.jpg"
  ,"/imgaes/315492528_425943316410051_7379856520568054418_n.jpg"]
            document.getElementById('img').src=imgs[index]
            index++;
            if(index==83){
                index=0
            }
        }
        setInterval(changeImage,2000)
    </script>
  </body>
</html>
