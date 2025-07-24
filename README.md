<!DOCTYPE html>
<html>
  <head>
    <title>VR Anywhere door</title>
    <script src="https://aframe.io/releases/0.4.0/aframe.min.js"></script>
 <script src="https://unpkg.com/aframe-simple-sun-sky@^1.2.3/simple-sun-sky.js"></script>

  </head>
  <body>
    <a-scene>

        <!--link-->
          <a-assest>
            <img id="floor" src="https://th.bing.com/th/id/OIP.VThjezl0rjrEk4oSLT-K8QHaE8?pid=ImgDet&rs=1">
            <img id="snow_wall_1" src="https://th.bing.com/th/id/OIP.-flTqkJ3tRQ0CvgkzfT0kQHaFz?pid=ImgDet&w=836&h=656&rs=1">
            <img id="snow_wall_2" src="https://cdn.pixabay.com/photo/2010/11/29/himalayas-409_960_720.jpg">
            <img id ="snow_base1" src="https://th.bing.com/th/id/R.a6a361887457015102daf96d2752e823?rik=lYMHkqrnqVsUtg&riu=http%3a%2f%2fwww.news1130.com%2fwp-content%2fblogs.dir%2fsites%2f9%2f2016%2f01%2f30%2fiStock_000013081040_Large-e1454191629185.jpg&ehk=iofmSR%2fviN0zV9QpTGMQmiRO0lEXJPxLxi1onWChdM8%3d&risl=&pid=ImgRaw&r=0">
            <img id="snow_wall_3" src="https://th.bing.com/th/id/R.73236a64be25cb9fae454d6e669b9a98?rik=Pm5rxHo%2bXFEo3A&riu=http%3a%2f%2fallpicts.in%2fwp-content%2fuploads%2f2016%2f05%2f10-Best-Nature-Images-HD-in-India-1-Munsiyari-in-Great-Himalayan-Mountain.jpg&ehk=yMk0RTCnY5wL1ZW01dzD7nfKVP6hF9Ux2oTWPDzCERU%3d&risl=&pid=ImgRaw&r=0">
            <img id="snow_wall_4" src="https://th.bing.com/th/id/R.7f657070025104a468456ada107aa7c1?rik=H579dbKIYD4LYw&riu=http%3a%2f%2fwallpapercave.com%2fwp%2fbjV4i7n.jpg&ehk=q8D3zhXCJ%2f3cejW6UPV2hdIJ%2fhyPGriZIqXawgW5Z%2bc%3d&risl=&pid=ImgRaw&r=0">
            <img id="snow_top" src="https://th.bing.com/th/id/R.ff887e7786516e91d92be52b0bf299ce?rik=whpLStk4ABd7wQ&riu=http%3a%2f%2fhdwpro.com%2fwp-content%2fuploads%2f2016%2f10%2fBlue-Sky-Image.jpg&ehk=FjI8nzTLqjeQw2cRjQs0kABFQIuFdOejI%2f5dZsab3Hk%3d&risl=&pid=ImgRaw&r=0">
            <img id="snow_floor" src="https://th.bing.com/th/id/OIP.VThjezl0rjrEk4oSLT-K8QHaE8?pid=ImgDet&rs=1">
            <img id="plain_wall" src="https://th.bing.com/th/id/OIP.rSe2WqSyocupFSXBQEv8SQHaE7?pid=ImgDet&w=640&h=426&rs=1">
            <img id="plain_wall_2" src="https://th.bing.com/th/id/OIP.VCqUJZdAT-GHFR5BGGJGSwHaEJ?pid=ImgDet&rs=1">
            <img id="plain_wall_3" src="https://th.bing.com/th/id/OIP.zM-TCEDhGC833c7s9Z6WoAHaE7?pid=ImgDet&rs=1">
            <img id="plain_wall_4" src="https://media-cdn.tripadvisor.com/media/photo-s/0f/cf/94/75/madakaripura-waterfall.jpg">
            <img id="plaintop" src="https://th.bing.com/th/id/OIP.KagLqHO521V2UeSotb-8YQHaEK?pid=ImgDet&w=980&h=551&rs=1">
            <img id="plain_base_1" src="https://th.bing.com/th/id/OIP.DQ2BMgALAvlSo5TdvGZvBgHaNL?pid=ImgDet&w=750&h=1334&rs=1">
            <img id="meditation portal" src="">
            <img id="s1" src="https://th.bing.com/th/id/OIP.Io1iTzWj3o8zgDdSUuR1TQHaEW?pid=ImgDet&rs=1">
            <img id="s2" src="https://th.bing.com/th/id/OIP.lJZVeG6Xz_q6Y_KaQN4tDAHaEo?pid=ImgDet&rs=1">
            <img id="s3" src="https://th.bing.com/th/id/OIP.GsJcaSrjYEIa-M4ajdVfnAHaEK?pid=ImgDet&rs=1">
            <img id="s4" src="https://th.bing.com/th/id/OIP._eI-uWlXB9Xd27s6htbfPgEwDN?pid=ImgDet&rs=1">
            <img id="fs" src="https://th.bing.com/th/id/OIP.UxxnVz3Nr8VjBAtkftceywHaEK?pid=ImgDet&rs=1">
            <img id="ts" src="https://th.bing.com/th/id/OIP.Gb5X30CATPuzv4bjDKR-mgHaEo?pid=ImgDet&rs=1">            
        </a-assest>
       <!-- SUN /SKY -->
<a-simple-sun-sky sun-position="-1 1 -1" light-color="#87cefa" dark-color="#00bfff" fog-color="#74d2fa"></a-simple-sun-sky>

         <!-- snow wall 1 -->
         <a-box src="#snow_wall_1" width="10" height="5" depth="0.1"  position="0 2.59 -5"></a-box>
         <!--snow wall 2 -->
         <a-box src="#snow_wall_2" width="10" height="0.1" depth="5" rotation="90 180 0" position="0 2.56 5" ></a-box>
   <!--snow floor -->
   <a-box scale="333 0.1 423" position="0 0 0 " src="#snow_floor"></a-box>
       <!--snow  base  -->
       <a-box position="-0.05 0.20 -0.03" rotation="0 0 0" scale="6.66 0.36 9.60" src="#snow_base1"geometry="width: 1.48"></a-box>
   <!--snow wall 3-->
        <a-box  src="#snow_wall_3" position="-4.97 2.50 0" scale="0.68 4.96 9.96"rotation="0 0 0" ></a-box>
        <!--snow top-->
        <a-box  width="10" height="0.1" depth="10"  position="0 4.99 0" rotation="180 0 0"src="#snow_top"></a-box>
        <!--snow wall 4-->
        <a-box width="0.1" height="5" depth="10"  position="5 2.58 0 "src="#snow_wall_4"></a-box>
        <!--plain wall-->
        <a-box width="0.0" height="5" depth="10"  position="7 2.58 0 "src="#plain_wall"></a-box>
        <!--plain wall 2-->
        <a-box src="#plain_wall_2" width="10" height="0.1" depth="5" rotation="90 180 0" position="11.97 2.56 5" ></a-box>
        <!--plain wall 3-->
        <a-box  src="#plain_wall_3" depth="1.00" height="1.00" width="0.00" position="16.94 2.55 0" scale="0.68 4.96 9.96"rotation="0 0 0" ></a-box>
        <!--plain wall 4-->
        <a-box src="#plain_wall_4" width="10" height="5" depth="0.1"  position="11.94 2.55 -5"></a-box>
        <!--plain base  -->
        <a-box geometry="depth: 1.04; height: 0.24; width: 1.4" position="11.96 0.07 0.05" rotation="0 0 0" scale="7.14 0.36 9.60" src="#plain_base_1"></a-box>
        <!--plain top-->
        <a-box  width="10" height="0.1" depth="10"  position="11.91 5.06 0.04" rotation="180 0 0"src="#plaintop"></a-box>
        <a-circle src="#meditation_portal" width="10" height="5" depth="0.1"  position="0 2.59 -5"></a-circle>
        <!--s1-->
        <a-box width="0.0" height="5.36" depth="9.18"  position="19.63 2.30 0.20 "src="#s1"></a-box>
        <!--s2-->
        <a-box src="#s2" width="9.20" height="0" depth="5" rotation="90 180 0" position="24.22 2.56 4.71" ></a-box>
        <!--s3-->
        <a-box  src="#s3" depth="0.90" height="1.00" width="0.00" position="28.85 2.55 0.18" scale="0.68 4.96 9.96"rotation="0 0 0" ></a-box>
        <!--s4-->
        <a-box src="#s4" width="9.4" height="5.04" depth="0"  position="24.30 2.42 -4.31"></a-box>
        <!--fs-->
        <a-box geometry="depth: 0.98; height: 0.00; width: 1.34" position="24.12 0.07 0.15" rotation="0 0 0" scale="7.14 0.36 9.60" src="#fs"></a-box>
        <!--ts-->
        <a-box  width="9.30" height="0.1" depth="8.94"  position="24.40 4.94 0.14" rotation="180 0 0"src="#ts"></a-box>
        
    </a-assest>
</body>
</html>
