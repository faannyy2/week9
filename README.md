
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dream Vacation Flights</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav class="container-fluid">
    <ul><li><strong>PHL ✈️ Dream Trips</strong></li></ul>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Deals</a></li>
      <li><a href="#" role="button">Book Now</a></li>
    </ul>
  </nav>

  <main class="container">
    <div class="grid">
      <section>
        <hgroup>
          <h2>Dream Vacation Destinations</h2>
          <h3>Round-Trip Flights from PHL</h3>
        </hgroup>
        <p>Explore top vacation destinations with affordable round-trip flights from Philadelphia International Airport.</p>
        
        <table>
          <thead>
            <tr>
              <th>Destination</th>
              <th>Price (USD)</th>
              <th>Airline</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Maldives</td>
              <td>$1,250</td>
              <td><a href="https://www.qatarairways.com" target="_blank">Qatar Airways</a></td>
            </tr>
            <tr>
              <td>Greece</td>
              <td>$980</td>
              <td><a href="https://www.turkishairlines.com" target="_blank">Turkish Airlines</a></td>
            </tr>
            <tr>
              <td>Egypt</td>
              <td>$890</td>
              <td><a href="https://www.egyptair.com" target="_blank">EgyptAir</a></td>
            </tr>
          </tbody>
        </table>
      </section>
    </div>
  </main>

  <section aria-label="Subscribe example">
    <div class="container">
      <article>
        <hgroup>
          <h2>Stay Updated</h2>
          <h3>Get exclusive flight deals in your inbox</h3>
        </hgroup>
        <form class="grid">
          <input type="text" id="firstname" name="firstname" placeholder="First name" aria-label="First name" required />
          <input type="email" id="email" name="email" placeholder="Email address" aria-label="Email address" required />
          <button type="submit" onclick="event.preventDefault()">Subscribe</button>
        </form>
      </article>
    </div>
  </section>

  <footer class="container">
    <small><a href="#">Privacy Policy</a> • <a href="#">Terms of Use</a></small>
  </footer>
</body>
</html>



