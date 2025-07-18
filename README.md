<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MD. A. K. M. RAZ | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Raz Portfolio</a>
    </div>
  </nav>

  <!-- About Section -->
  <section class="container my-5" id="about">
    <div class="row">
      <div class="col-md-4 text-center">
        <img src="assets/profile.jpg" class="img-fluid rounded-circle" alt="Profile Photo" width="200">
      </div>
      <div class="col-md-8">
        <h2>About Me</h2>
        <p>
          I’m <strong>MD. A. K. M. RAZ</strong>, a passionate Textile Engineer specializing in lab testing, textile production, and sustainable innovation.
          Currently working at <strong>Hohenstein Laboratories Bangladesh Ltd</strong>. I enjoy research, smart textiles, and hands-on problem solving.
        </p>
        <a href="resume.pdf" class="btn btn-primary mt-2" download>📄 Download Resume</a>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="bg-light py-5" id="projects">
    <div class="container">
      <h2 class="text-center mb-4">Projects</h2>
      <div class="row">
        <!-- Project 1 -->
        <div class="col-md-4">
          <div class="card h-100">
            <img src="assets/project1.jpg" class="card-img-top" alt="Project 1">
            <div class="card-body">
              <h5 class="card-title">Fabric Strength Testing</h5>
              <p class="card-text">ISO standard test report on woven fabric tensile strength and tear resistance.</p>
              <a href="https://drive.google.com/yourlink1" class="btn btn-sm btn-outline-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-md-4">
          <div class="card h-100">
            <img src="assets/project2.jpg" class="card-img-top" alt="Project 2">
            <div class="card-body">
              <h5 class="card-title">Dyeing Lab Report</h5>
              <p class="card-text">Dyeing fastness report and evaluation for different fiber types (cotton, polyester).</p>
              <a href="https://drive.google.com/yourlink2" class="btn btn-sm btn-outline-primary" target="_blank">View Project</a>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-md-4">
          <div class="card h-100">
            <img src="assets/project3.jpg" class="card-img-top" alt="Project 3">
            <div class="card-body">
              <h5 class="card-title">Internship Report</h5>
              <p class="card-text">Complete industrial internship documentation on spinning, weaving, and testing labs.</p>
              <a href="https://www.scribd.com/document/869774310/Internship-Report" class="btn btn-sm btn-outline-primary" target="_blank">Read Report</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="container py-5" id="contact">
    <h2 class="text-center mb-4">Contact</h2>
    <div class="row">
      <div class="col-md-6">
        <h5>Let's Connect</h5>
        <p>Email: <a href="mailto:akmraz36@gmail.com">akmraz36@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/akmraz10" target="_blank">linkedin.com/in/akmraz10</a></p>
        <p>YouTube: <a href="https://www.youtube.com/@TheRazEffect" target="_blank">@TheRazEffect</a></p>
        <p>Telegram: <a href="https://t.me/textileresarch" target="_blank">@textileresarch</a></p>
      </div>
      <div class="col-md-6">
        <form action="https://formspree.io/f/yourformid" method="POST">
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" name="name" required/>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Your Email</label>
            <input type="email" class="form-control" name="email" required/>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" name="message" rows="4" required></textarea>
          </div>
          <button type="submit" class="btn btn-success">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    © 2025 MD. A. K. M. RAZ | Built with ❤️
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
