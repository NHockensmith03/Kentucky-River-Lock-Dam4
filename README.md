

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
      background-color: rgb(236, 232, 228);
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
      color: rgb(12, 73, 34);
    }

    a:hover {
      color: rgb(86, 86, 86);
      text-decoration: none;
    }

    section {
      width: 80%;
      margin: 0 auto;
    }

    footer {
      width: 80%;
      margin: 0 auto;
      color: rgb(100, 100, 100);
    }

    iframe {
      border: 1px solid rgb(200, 200, 200);
      border-radius: 10px;
      margin-top: 20px;
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
      flex-basis: 55%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Define styles for the right column */
    .right-column {
      flex-basis: 55%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Round image corners for images inside the right-column */
    .right-column img {
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
  </style>
</head>

<body>
  <section>
    <!-- 💡💡💡 Cesium map: paste embed code below -->
    <iframe title="KyRivLoc4" width="1024" height="576" src="https://ion.cesium.com/stories/viewer/?id=81198725-83d1-423c-84cb-33141159165e" frameborder="0" allow="fullscreen" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    <!-- 💡💡💡 Cesium map: paste embed code above -->
    <p class="caption">Above is an 3D tour of the Kentucky River Lock & Dam #4 </p>
    <div class="title">
      <h1>Kentukcy River Lock & Dam #4</h1>
      <h2>Frankfort, Kentucky</h2>
    </div>
    <div class="container">
      <div class="left-column">
        <h3>Left Column - Description</h3>
        <p>
          The original lock and Dam #4 on the Kentucky River was built between the years 1836 to 1842 and was then rebult in 1882 by the Corp of Engineers. The Lock & Dam have since been repaired several time and are still currently operational to leasure boat traffic, though the locks were used until 2002 as a form of transportation of goods by barge.
        </p>
        <p>
          The goal of this project is to take a look at a piece of infustructure that played a role in the growth of kentucky. The lock system throughout the kentucky river played a viable role in transportation of good in and out of the state. 
        </p>
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
      </div>
      <div class="right-column">
        <h3>Shaded Relief </h3>
        <img src="KyRivShadeRelief.jpg" alt="Something about this map" width="100%" />
        <p class="caption">This map displays a shaded releif of the area around Lock #4 <a href="KyRivShadeRelief.pdf">(High-Resolution Version)</a></p>
        <h3>Point Cloud from Lidar </h3>
      <img src="KyRivLoc4_Map.jpg" alt="Something about this map" width="100%" />
        <p class="caption">This map the size of the lock determined from lidar data being displayed as a colorized point cloud. <a href="KyRivLoc4_Map.pdf">(High-Resolution Version)</a></p>
      </div>
    </div>
  </section>
  <footer>
    <hr />
    <img src="logo-color-400px.png" alt="UKy Arts and Sciences  " width="300px">
  </footer>
</body>
