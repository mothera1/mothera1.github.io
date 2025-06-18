


<head>
  <title>Marcus Rothera – Projects</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[url(stars.jpg)] font-mono text-gray-800">

  <!-- Navbar -->
  <nav class="bg-black text-white py-4 shadow-md">
    <ul class="flex justify-center gap-10 font-bold">
      <li><a href="/">Home</a></li>
      <li><a href="/projects">Projects</a></li>
      <li><a href="/lucky">Personal</a></li>
    </ul>
  </nav>

  <!-- Main Projects Section -->
  <main class="max-w-5xl mx-auto px-6 py-10 space-y-10">

    

    <!-- Spinalytics Project Card -->
    <section class="bg-white p-6 rounded-2xl shadow-lg border border-black">
      <h2 class="text-2xl font-bold text-center text-black mb-4">Spinalytics</h2>
      <h3 class="text-lg font-semibold mb-2">About</h3>
      <p class="text-sm leading-relaxed text-gray-700">
        As General Manager of WZBC Newton 90.3 FM, I developed
        <a href="http://spinalytics.s3-website.us-east-2.amazonaws.com/" class="text-black hover:underline">Spinalytics</a>, 
        a faux “Spotify Wrapped” for radio shows. It details the top artists, songs, and genres 
        for 3 shows. I used Scrapy to extract data from 
        <a href="https://spinitron.com/WZBC/calendar" class="text-black hover:underline">Spinitron</a>, 
        stored it in AWS Timestream DB, and built a full pipeline using Lambda, API Gateway, Postman, and S3 for the React frontend. 
        It’s still under active development, with plans to expand coverage to all WZBC shows.
      </p>
      <img src="Spindia.png" alt="Spinalytics screenshot" class="w-full max-w-2xl mx-auto rounded-lg mb-4">
      
    </section>

    <!-- SBIR Project Card -->
    <section class="bg-white p-6 rounded-2xl shadow-lg border border-black">
      <h2 class="text-2xl font-bold text-center text-black mb-4">SBIR Database Analysis</h2>
      <h3 class="text-lg font-semibold mb-2">About</h3>
      <p class="text-sm leading-relaxed text-gray-700">
        This analysis was conducted during my internship at
        <a href="https://theoutpost.com/" class="text-black hover:underline">The Outpost</a>. 
        Data was collected from the 
        <a href="https://www.sbir.gov/awards" class="text-black hover:underline">SBIR Award Database</a>, 
        and the descriptions were vectorized using OpenAI’s ada model and TF-IDF. 
        These vectors were reduced using UMAP and clustered with HDBSCAN and K-Means. 
        Insights helped account managers better match clients with DoD contract sectors.
      </p>
      <img src="KMEANS.png" alt="KMeans Clustering" class="w-full max-w-2xl mx-auto rounded-lg mb-4">
      
    </section>

  </main>
</body>