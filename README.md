<head>
  <meta charset="utf-8" />
  <title>Presentation</title>
  <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;800&display=swap" rel="stylesheet" />
  <style>
    /* Set margin/padding to fit border in box model */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    /* Define styles on body (and all descendants) */
    body {
      margin: 0;
      padding: 0;
      font-family: "Open Sans", sans-serif;
      font-weight: 400;
      color: rgb(32, 32, 32);
      background-color: rgba(35, 70, 34, 0.55);
    }
    /* Define styles for the headings */
    h1 {
      font-size: 3rem;
      font-weight: 800;
      margin: 10px 0;
      padding: 0;
      color: rgb(0, 0, 0);
    }
    h2 {
      font-size: 2rem;
      font-weight: 800;
      margin: 0;
      padding: 0;
    }
    h3 {
      font-size: 1.5rem;
      font-weight: bold;
      margin-bottom: 10px;
    }
    /* Define styles for the paragraph */
    p {
      font-size: 1.3rem;
      font-weight: 400;
      margin: 0 0 10px 0;
      padding: 0;
    }
    a:link,
    a:visited {
      color: rgb(255, 0, 0);
    }
    a:hover {
      color: rgb(252, 7, 235);
      text-decoration: none;
    }
    section {
      width: 100%;
      margin: 0 auto;
    }
    footer {
      width: 100%;
      margin: 0 auto;
      color: rgb(124, 123, 123);
    }
    iframe {
    width: 100%;
    max-width: 100%;
    height: auto;
    border: 1px solid rgb(200, 200, 200);
    border-radius: 10px;
    margin-top: 20px;
    }
    iframe.responsive {
  width: 100%;
  aspect-ratio: 16 / 9; 
  border: none;
  }
    .caption {
      font-size: 0.8rem;
      font-weight: 400;
      font-style: italic;
      margin: 0;
      padding: 0;
      color: rgb(100, 100, 100);
    }
    .title {
      text-align: left;
      margin: 20px;
    }
    /* Set up a container for the two columns */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }
    /* Define styles for the left column */
    .left-column {
      flex-basis: 48%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }
    /* Define styles for the right column */
    .right-column {
      flex-basis: 48%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }
    /* Round image corners for images inside the right-column */
    .right-column img {
      border-radius: 10px;
    }
     /* Round image corners for images inside the left-column */
    .left-column img {
      border-radius: 10px;
    }
    /* Media query for small screens */
    /* For screens up to 768px, apply these rules. */
    @media (max-width: 768px) {
      /* Change to a single column layout */
      .container {
        flex-direction: column;
      }
      /* Set full width for both columns */
      .left-column,
      .right-column {
        flex-basis: 100%;
      }
    }
    .content {
      text-align: center;    /* centers inline & inline-block children */
      padding: 2rem;
    }
  </style>
</head>
<body>
  <section>
    <!-- 💡💡💡 Cesium map: paste embed code below -->
    <iframe 
    class="responsive"
    title="KyRivLoc4" width="1024" height="576" src="https://ion.cesium.com/stories/viewer/?id=81198725-83d1-423c-84cb-33141159165e" frameborder="0" allow="fullscreen" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    <!-- 💡💡💡 Cesium map: paste embed code above -->
    <p class="caption">Above is an 3D tour of the Kentucky River Lock & Dam #4, Explore the Cesium Ion slideshow via the above controls (CTRL or ⌘ + click to rotate).</p>
    <div class="title">
      <h1>Kentukcy River Lock & Dam #4</h1>
      <h2>Frankfort, Kentucky</h2>
    </div>
    <div class="container">
      <div class="left-column">
        <h3>History</h3>
        <p>
          The Kentucky River has been used for travel and trade of goods even before Kentucky became the fifteenth state. There is documentation of a trip from Frankfort, KY, to New Orleans, LA in 1787. This trip being a part of the Kentucky-Mississippi River Trade Route. This Trade route allowed trade between New Orleans, Louisville, Cincinnati, and Central Kentucky. The trade route was hard to travel when the water was low, so locks 1 through 5 on the Kentucky River were constructed from 1836 to 1842. Including the original lock and Dam #4, which was then rebuilt in 1882 by the Corps of Engineers. The Lock & Dam have since been repaired several times and are still currently operational to leisure boat traffic. However, the locks were used until 2002 as a form of transportation of goods by barge at this point locks 1 through 4 were leased from the United States Army Corps to the Kentucky River Authority, that was established in 1986 to manage locks 5 through 14 on the Kentucky River until they were decommissioned in 1990.
        </p>
        <h3>Purpose</h3>
        <p>
         The goal of this project is to take a look at a piece of infrastructure that played an important role in the growth of Kentucky, using aerial imagery and Lidar data to create 3D Point cloud models.
        </p>
        <h3>Credits</h3>
        <p>
          Visualizations created from lidar data provided by
          <a href="https://kyfromabove.ky.gov/">KyFromAbove</a> in ArcGIS Pro, Blender, and Cesium Ion. Additional sources of information from
          <a href="https://finance.ky.gov/kentucky-river-authority/Documents/2_Intro_Ky_River_Trans_Route.pdf">Kentucky.gov</a>, and
          <a href="https://finance.ky.gov/kentucky-river-authority/Pages/lock-and-dam-4.aspx#:~:text=Lock%20and%20Dam%204%20were,original%20lock%20was%20stone%20masonry.">Kentucky River Authority</a>, April, 2025.
        </p>
        <p>
          Page and visualizations created by NHockensmith for GEO 409, Department of
          Geography, University of Kentucky. Spring 2025.
        </p>
        <h3>Signage Near Lock #4 </h3>
        <img src="LocSign.jpg" alt="Something about this map" width="100%" />
        <p class="caption">Picture of sign near Kentucky River Lock & Dam #4 by Nick Hockensmith. 
        </p>
      </div>
      <div class="right-column">
        <h3>Shaded Relief </h3>
        <img src="KyRivShadeRelief.jpg" alt="Something about this map" width="100%" />
        <p class="caption">This map displays a shaded releif of the area around Lock #4 <a href="KyRivShadeRelief.pdf">(High-Resolution Version)</a></p>
        <h3>Point Cloud from Lidar </h3>
      <img src="KyRivLoc4_Map.jpg" alt="Something about this map" width="100%" />
        <p class="caption">This map the size of the lock determined from lidar data being displayed as a colorized point cloud. <a href="KyRivLoc4_Map.pdf">(High-Resolution Version)</a></p>
        <h3>North East Facing Picture </h3>
        <img src="Lock4.3.jpg" alt="Something about this map" width="100%" />
        <p class="caption">Picture of Kentucky River Lock & Dam #4 from the west side of the river facing north east by Nick Hockensmith.
         </p> 
        <h3>South East Facing Picture </h3>
        <img src="Lock4.1.jpg" alt="Something about this map" width="100%" />
        <p class="caption">Picture of Kentucky River Lock & Dam #4 from the west side of the river facing south east by Nick Hockensmith 
        </p>
        <h3>North West Facing Picture </h3>
        <img src="Lock4.2.jpg" alt="Something about this map" width="100%" />
        <p class="caption">Picture of Kentucky River Lock & Dam #4 from the east side of the dam facing north west by Nick Hockensmith.
        </p>
      </div>
    </div>
  </section>
<div class="content">
  <footer>
    <hr />
    <img src="logo-color-400px.png" alt="UKY College of Arts and Sciences" width="300px">
  </footer>
  </div>
</body>
