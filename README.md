<!DOCTYPE html>
<html lang="en">
   <head>
      <title> :: MANI XDIN FM ::</title>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script> <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script> 
      <link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
      <link href="https://unpkg.com/video.js/dist/video-js.css" rel="stylesheet">
      <script src="https://unpkg.com/video.js/dist/video.js"></script> <script src="https://unpkg.com/videojs-contrib-hls/dist/videojs-contrib-hls.js"></script> 
      <style type="text/css">body{min-height:100vh;background:#fff}.fm-container,.fm-container-air{padding:0px 0px;border:1px solid #000;margin-bottom:10px}.fm-container2{padding:0px;margin-bottom:10px}.main-title{color:#FFA500}.main-title2{color:#fff}.lightmode{display:none;background:#fff;color:#000;width:35px;height:35px;line-height:32px;border-radius:50%;text-align:center;position:absolute;top:10px;right:10px}.nightmode{background:#000;color:#fff;width:35px;height:35px;line-height:32px;border-radius:50%;text-align:center;position:absolute;top:10px;right:10px}.fm-static-container{background:linear-gradient(to right, #232526, #414345);position:fixed;top:0px;width:100%;padding:10px 10px 10px 10px;z-index:9999;border-bottom:2px solid #d2d2d2}.footer-static-container{background:linear-gradient(to right, #232526, #414345);position:fixed;bottom:0px;width:100%;padding:10px 10px 10px 10px;z-index:9999;border-top:2px solid #d2d2d2;text-align:center}.mt-top{margin-top:115px}footer{margin-bottom:60px}.fm-container img, .fm-container-air img{width:100%;height:auto}.fm-container p, .fm-container-air p{font-size:10px}.sub-title{text-align:center;margin:20px 0px}.col-4{padding-right:7px!important;padding-left:7px!important}.pause-div,.unmute-div{display:none}audio{height:0px;display:none}.btn{border-radius:21px;width:100px}footer{width:100%;height:50px;background:#000;text-align:center}footer p{color:#fff;line-height:50px}footer p a{color:orange!important}.loading{position:fixed;top:0;right:0;bottom:0;left:0;background:#ffffffcc;z-index:99999;height:100vh;display:none}.loader{width:250px;height:auto;display:block;position:absolute;top:50%;left:50%;transform:translate(-50%, -50%)}.video-js .vjs-tech{height:20px}.video-js{display:none}</style>
   </head>
   <body>
      <div class="loading"> <img class="loader" src="https://i.pinimg.com/originals/48/6a/a0/486aa0fa1658b7522ecd8918908ece40.gif" /></div>
      <div class="fm-static-container">
         <h2 class="text-center main-title">TAMIL VM FM</h2>
         <p class="nightmode text-center"> <i class="fa fa-moon-o"></i></p>
         <p class="lightmode text-center"> <i class="fa fa-sun-o"></i></p>
         <div class="row">
            <div class="col-md-12">
               <div class="fm-container2 text-center" data-link="https://azuracast.vibesounds.in:8000/radio.mp3" data-title="Sahara FM">
                  <h4 class="fm-name mb-2 main-title2" >Sahara FM</h4>
                  <audio id="player" controls>
                     <source id="fm-url" src="https://azuracast.vibesounds.in:8000/radio.mp3" type="audio/mpeg">
                  </audio>
                  <video id="my_video_1" class="video-js vjs-fluid vjs-default-skin" controls preload="auto" data-setup='{}'>
                     <source src="https://air.pc.cdn.bitgravity.com/air/live/pbaudio050/playlist.m3u8" type="application/x-mpegURL">
                  </video>
               </div>
            </div>
         </div>
      </div>
      <div class="footer-static-container">
         <div class="row">
            <div class="col-6 pause-div "> <button class="btn btn-secondary pause">Pause</button></div>
            <div class="col-6 play-div "> <button class="btn btn-secondary play">Play</button></div>
            <div class="col-6 mute-div "> <button class="btn btn-warning mute">Mute</button></div>
            <div class="col-6 unmute-div "> <button class="btn btn-warning unmute">Unmute</button></div>
         </div>
      </div>
      <div class="container mt-top">
         <h4 class="sub-title">All India Radio</h4>
         <div class="row">
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio050/chunklist.m3u8" data-title="AIR Karaikal">
                  <img src="http://veera4u.mobie.in/kaaraikkalfm.jpeg">
                  <p class="mb-3 mt-2">AIR Karaikal</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio051/playlist.m3u8" data-title="AIR Kodaikanal">
                  <img src="http://veera4u.mobie.in/KODAIFM.png">
                  <p class="mb-3 mt-2">AIR Kodaikanal</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio017/playlist.m3u8" data-title="AIR Coimbtore">
                  <img src="https://www.tamilradios.com/assets/img/radio-logos/air-coimbatore-am-999.jpg">
                  <p class="mb-3 mt-2">AIR Coimbtore</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio041/playlist.m3u8" data-title="AIR Trichy">
                  <img src="https://manixdin.github.io/mrxdinfm/img/air/trichy.jpg">
                  <p class="mb-3 mt-2">AIR Trichy</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio022/playlist.m3u8" data-title="AIR Chennai">
                  <img src="https://manixdin.github.io/mrxdinfm/img/air/chennai.jpg">
                  <p class="mb-3 mt-2">AIR Chennai</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container-air text-center" data-link="https://air.pc.cdn.bitgravity.com/air/live/pbaudio025/playlist.m3u8" data-title="AIR Tamil">
                  <img src="https://manixdin.github.io/mrxdinfm/img/air/chennai.jpg">
                  <p class="mb-3 mt-2">AIR Tamil</p>
               </div>
            </div>
         </div>
         <h4 class="sub-title">FM Channel</h4>
         <div class="row">
            <!-- <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://freeuk29.listen2myradio.com/live.mp3?typeportmount=s1_36366_stream_981344634" data-title="MR XDIN FM">
                  <img src="http://tamilvmfm.mobie.in/airtamil.jpg">
                  <p class="mb-3 mt-2">MR XDIN FM</p>

                  
               </div>
            </div> -->
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://kummalam.stream.laut.fm/kummalam" data-title="kummalam FM">
                  <img src="https://www.tamilradios.com/assets/img/radio-logos/kummalam-radio.jpg">
                  <p class="mb-3 mt-2">kummalam FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://cp1.hostcrate.com/8910/stream" data-title="isaiaruvi fm">
                  <img src="https://www.tamilradios.com/assets/img/radio-logos/isaiaruvi-fm.jpg">
                  <p class="mb-3 mt-2">isaiaruvi fm</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://a9oldhits-a9media.radioca.st/stream" data-title="Palaiya Padal FM">
                  <img src="https://radiosindia.com/images/a9radio.jpg">
                  <p class="mb-3 mt-2">Palaiya Padal FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://www.liveradio.es/http://radio.lotustechnologieslk.net:8006/;stream.mp3" data-title="Suryan FM">
                  <img src="https://onlineradiofm.in/assets/image/radio/180/sooriyan.webp">
                  <p class="mb-3 mt-2">Suryan FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://www.liveradio.es/http://220.247.227.20:8000/Threndralstream" data-title="Thenral Radio">
                  <img src="http://veera4u.mobie.in/a thendral fm.jpg">
                  <p class="mb-3 mt-2">Thenral Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://usa9.fastcast4u.com/proxy/nesaganam?mp=/1" data-title="Nesaganam">
                  <img src="https://onlineradiofm.in/assets/image/radio/180/karaikal.jpg">
                  <p class="mb-3 mt-2">Nesaganam</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://www.liveradio.es/http://104.200.16.182:8000/;stream.mp3" data-title="Pollachi FM">
                  <img src="https://www.tamilradios.com/assets/img/radio-logos/pollachi-tamil-fm.jpg">
                  <p class="mb-3 mt-2">Pollachi FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/puthupaadalradio" data-title="Puthu Paadal Radio">
                  <img src="http://veera4u.mobie.in/anuradhafm_1.jpg">
                  <p class="mb-3 mt-2">anuradha Radio</p>
               </div>
            </div>
         </div>
         <h4 class="sub-title">Artist</h4>
         <div class="row">
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/anirudhradio" data-title="Aniruth FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/aniruth.jpg">
                  <p class="mb-3 mt-2">Aniruth FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://apipermission.southradios.net/play/spbradio" data-title="SPB FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/spb.jpg">
                  <p class="mb-3 mt-2">SPB FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/ysrradio" data-title="Yuvan FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/yuvan.jpg">
                  <p class="mb-3 mt-2">Yuvan FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://southradios.net/play/arrahmanradio" data-title="AR Rahman FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/arrahman.jpg">
                  <p class="mb-3 mt-2">AR Rahman FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/ilayarajaradio" data-title="ILAYARAJA FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/ilayaraja.jpg">
                  <p class="mb-3 mt-2">Ilayaraja FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/kschitra" data-title="KS Chitra">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/ks-chitra.jpg">
                  <p class="mb-3 mt-2">KS Chitra</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/immanradio" data-title="Imman Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/imman.jpg">
                  <p class="mb-3 mt-2">Imman Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/manoradio" data-title="Mano Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/Mano.jpg">
                  <p class="mb-3 mt-2">Mano Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/gvprakashradio" data-title="GV Prakash Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/gvprakash.jpg">
                  <p class="mb-3 mt-2">GV Prakash Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/hariharanradio" data-title="Hariharan Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/hariharan.jpg">
                  <p class="mb-3 mt-2">Hariharan Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/unnikrishanradio" data-title="Unnikrishnan Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/unikrishnan.jpg">
                  <p class="mb-3 mt-2">Unnikrishnan Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/mellisaimannarradio" data-title="Mellisai Mannar Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/artist/mellisaimannar.jpg">
                  <p class="mb-3 mt-2">Mellisai Mannar</p>
               </div>
            </div>
         </div>
         <h4 class="sub-title">Actor</h4>
         <div class="row">
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://stream.zeno.fm/1gr8v0m4g2zuv" data-title="Vijay Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/vijay.jpg">
                  <p class="mb-3 mt-2">Vijay Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://stream.zeno.fm/qfkksd31w0hvv" data-title="Ajith FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/ajith.jpg">
                  <p class="mb-3 mt-2">Ajith FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/superstarradio" data-title="Super Star Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/rajini.jpg">
                  <p class="mb-3 mt-2">Super Star Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/kalaignanairadio" data-title="Kamal Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/kamal.jpg">
                  <p class="mb-3 mt-2">Kamal Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/sivajiradio" data-title="Sivaji Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/sivaji.jpg">
                  <p class="mb-3 mt-2">Sivaji Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/mgradio" data-title="MGR Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/mgr.jpg">
                  <p class="mb-3 mt-2">MGR Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/thalathalapathyradio" data-title="Thala Thalapathy Radio">
                  <img src="http://veera4u.mobie.in/vijayakanthfm.jpeg">
                  <p class="mb-3 mt-2">Vijayakanth Fm</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/mohanradio" data-title="Mohan Hits Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/mohan.jpg">
                  <p class="mb-3 mt-2">Mohan Hits Radio</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="https://southradios.net/play/gvprakashradio" data-title="GV Prakash Radio">
                  <img src="https://manixdin.github.io/mrxdinfm/img/actor/gv.jpg">
                  <p class="mb-3 mt-2">GV Prakash Radio</p>
               </div>
            </div>
         </div>
         <h4 class="sub-title">God</h4>
         <div class="row">
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://stream.zeno.fm/0p1p4t7043duv" data-title="Bakthi FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/god/bakthi.png">
                  <p class="mb-3 mt-2">Bakthi FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://24963.live.streamtheworld.com/OMRADIO_S01AAC_SC" data-title="OM FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/god/om.jpg">
                  <p class="mb-3 mt-2">OM FM</p>
               </div>
            </div>
            <div class="col-md-2 col-4">
               <div class="fm-container text-center" data-link="http://stream.zeno.fm/up95n0xf84zuv" data-title="Ayyappa Tamil FM">
                  <img src="https://manixdin.github.io/mrxdinfm/img/god/ayyappan.jpg">
                  <p class="mb-3 mt-2">Ayyappa Tamil FM</p>
               </div>
            </div>
         </div>
      </div>
      </div>
      <footer>
         <p>Designed by <a href="https://sites.google.com/view/tamilvmfm/home/" target="_blank">VEERA 4U</a></p>
      </footer>
      <script type="text/javascript">$(document).ready(function(){var type="audio";$('.fm-container-air').click(function(){var audio=$("#player");audio[0].pause();type="video";$('.play-div').hide();$('.pause-div').show();$('.unmute-div').hide();$('.mute-div').show();$('.loading').show().fadeOut(1500);var title=$(this).attr('data-title');var link=$(this).attr('data-link');console.log(link);$('.fm-name').text(title);var player=videojs('my_video_1');player.src({"src":link,"type":'application/x-mpegurl'});player.load();player.play();});$('.nightmode').click(function(){$('h6,h5,h4,h3,h2,h1,p').css({'color':'#fff'});$('i').css({'color':'#000'});$('body').css({'background':'#000'});$('.fm-container').css({'border':'1px solid #fff'});$('.lightmode').show();$('.nightmode').hide();});$('.lightmode').click(function(){$('h6,h5,h4,h3,h2,h1,p').css({'color':'#000'});$('i').css({'color':'#fff'});$('body').css({'background':'#fff'});$('.fm-container').css({'border':'1px solid #000'});$('.lightmode').hide();$('.nightmode').show();$('.main-title').css({'color':'#FFA500'});$('.main-title2').css({'color':'#ffffff'});});$('.fm-container').click(function(){$('video').each(function(index){$(this).get(0).pause();});type="audio";$('.play-div').hide();$('.pause-div').show();$("#player").prop('muted',false);$('.unmute-div').hide();$('.mute-div').show();$('.loading').show();var title=$(this).attr('data-title');var link=$(this).attr('data-link');$('.fm-name').text(title);var audio=$("#player");$("#fm-url").attr("src",link);audio[0].pause();audio[0].load();audio[0].oncanplaythrough=audio[0].play();});$("#player").bind('playing',function(){$('.loading').hide();});$('.pause').click(function(){if(type=="audio"){var audio=$("#player");audio[0].pause();} else{$('video').each(function(index){$(this).get(0).pause();});} $('.pause-div').hide();$('.play-div').show();});$('.play').click(function(){if(type=="audio"){var audio=$("#player");audio[0].load();audio[0].oncanplaythrough=audio[0].play();} else{$('video').each(function(index){$(this).get(0).play();});} $('.play-div').hide();$('.pause-div').show();});$('.mute').click(function(){if(type=="audio"){$("#player").prop('muted',true);} else{$("video").prop('muted',true);} $('.mute-div').hide();$('.unmute-div').show();});$('.unmute').click(function(){if(type=="audio"){$("#player").prop('muted',false);} else{$("video").prop('muted',false);} $('.unmute-div').hide();$('.mute-div').show();});});</script> 
   </body>
</html>

