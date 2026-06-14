# index.html
<!-- SOAL 1 -->
<section id="lineup">
  <div class="container">
    <span class="soal-label">Soal 1 — Grid Bootstrap</span>
    <h2 class="section-title">Lineup Artis</h2>

    <div class="row">

      <div class="col-12 col-md-6 col-lg-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A1">
          <h5>Rocket Ignition</h5>
          <p>Hard Rock | Jakarta</p>
        </div>
      </div>

      <div class="col-12 col-md-6 col-lg-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A2">
          <h5>Midnight Echo</h5>
          <p>Indie Pop | Bandung</p>
        </div>
      </div>

      <div class="col-12 col-md-6 col-lg-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A3">
          <h5>Thunder Hollow</h5>
          <p>Metal | Surabaya</p>
        </div>
      </div>

      <div class="col-12 col-md-6 col-lg-4 mt-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A4">
          <h5>The Wanderers</h5>
          <p>Acoustic | Yogyakarta</p>
        </div>
      </div>

      <div class="col-12 col-md-6 col-lg-4 mt-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A5">
          <h5>Solar Drift</h5>
          <p>Psychedelic | Bali</p>
        </div>
      </div>

      <div class="col-12 col-md-6 col-lg-4 mt-4">
        <div class="artist-card">
          <img src="https://via.placeholder.com/80/e94560/ffffff?text=A6">
          <h5>Iron Canvas</h5>
          <p>Progressive | Medan</p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- SOAL 2 -->
<section id="jadwal">
  <div class="container">
    <span class="soal-label">Soal 2 — Tabel Bootstrap</span>
    <h2 class="section-title">Jadwal Penampilan</h2>

    <div class="table-responsive">
      <table class="table table-bordered table-striped table-hover table-dark">

        <thead class="thead-dark">
          <tr>
            <th>Hari</th>
            <th>Waktu</th>
            <th>Artis</th>
            <th>Genre</th>
            <th>Panggung</th>
          </tr>
        </thead>

        <tbody>
          <tr>
            <td>Hari 1</td>
            <td>18.00-19.30</td>
            <td>The Wanderers</td>
            <td>Acoustic</td>
            <td>Stage B</td>
          </tr>

          <tr>
            <td>Hari 1</td>
            <td>20.00-22.00</td>
            <td>Midnight Echo</td>
            <td>Indie Pop</td>
            <td>Main Stage</td>
          </tr>

          <tr>
            <td>Hari 2</td>
            <td>17.00-18.30</td>
            <td>Solar Drift</td>
            <td>Psychedelic</td>
            <td>Stage B</td>
          </tr>

          <tr>
            <td>Hari 2</td>
            <td>19.30-21.30</td>
            <td>Thunder Hollow</td>
            <td>Metal</td>
            <td>Main Stage</td>
          </tr>

          <tr>
            <td>Hari 3</td>
            <td>18.00-19.00</td>
            <td>Iron Canvas</td>
            <td>Progressive</td>
            <td>Stage B</td>
          </tr>

          <tr>
            <td>Hari 3</td>
            <td>20.00-22.30</td>
            <td>Rocket Ignition</td>
            <td>Hard Rock</td>
            <td>Main Stage</td>
          </tr>
        </tbody>

      </table>
    </div>
  </div>
</section>

<!-- SOAL 3 -->
<section id="daftar">
  <div class="container">
    <span class="soal-label">Soal 3 — Form Bootstrap</span>
    <h2 class="section-title">Beli Tiket</h2>

    <div class="row justify-content-center">
      <div class="col-md-7">

        <div class="card card-body">

          <div class="form-group">
            <label>Nama Lengkap</label>
            <input type="text" class="form-control">
          </div>

          <div class="form-group">
            <label>Email</label>
            <input type="email" class="form-control">
          </div>

          <div class="form-group">
            <label>Nomor Telepon</label>
            <input type="tel" class="form-control">
          </div>

          <div class="form-group">
            <label>Jenis Tiket</label>
            <select class="form-control">
              <option>Regular</option>
              <option>VIP</option>
              <option>VVIP</option>
            </select>
          </div>

          <div class="form-group">
            <label>Jumlah Tiket</label>
            <input type="number" class="form-control" value="1">
            <small class="form-text text-muted">
              Maksimal pembelian 10 tiket.
            </small>
          </div>

          <div class="form-group">
            <div class="form-check">
              <input type="checkbox" class="form-check-input">
              <label class="form-check-label">
                Saya menyetujui syarat dan ketentuan.
              </label>
            </div>
          </div>

          <button class="btn btn-danger btn-block">
            Beli Tiket Sekarang
          </button>

        </div>

      </div>
    </div>
  </div>
</section>

<!-- SOAL 4 -->
<section id="harga">
  <div class="container">
    <span class="soal-label">Soal 4 — Implementasi Wireframe</span>
    <h2 class="section-title">Harga Tiket</h2>

    <div class="row">

      <div class="col-12 col-md-4 mb-4">
        <div class="ticket-card">
          <div class="type">Regular</div>
          <div class="price">Rp150.000</div>

          <ul class="text-left mt-3">
            <li>Akses Area Festival</li>
            <li>Menonton Semua Artis</li>
            <li>Free Sticker Event</li>
          </ul>

          <button class="btn btn-danger btn-block">
            Beli Tiket
          </button>
        </div>
      </div>

      <div class="col-12 col-md-4 mb-4">
        <div class="ticket-card">
          <div class="type">VIP</div>
          <div class="price">Rp350.000</div>

          <ul class="text-left mt-3">
            <li>Area VIP</li>
            <li>Fast Track Entry</li>
            <li>Merchandise Premium</li>
          </ul>

          <button class="btn btn-warning btn-block">
            Beli Tiket
          </button>
        </div>
      </div>

      <div class="col-12 col-md-4 mb-4">
        <div class="ticket-card">
          <div class="type">VVIP</div>
          <div class="price">Rp750.000</div>

          <ul class="text-left mt-3">
            <li>Meet & Greet</li>
            <li>Backstage Access</li>
            <li>Souvenir Eksklusif</li>
          </ul>

          <button class="btn btn-success btn-block">
            Beli Tiket
          </button>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- SOAL 5 -->
<section id="kontak">
  <div class="container">
    <span class="soal-label">Soal 5 — Kreativitas Desain</span>
    <h2 class="section-title">Hubungi Kami</h2>

    <div class="row">

      <div class="col-md-6 mb-4">
        <div class="card bg-dark text-white border-danger">
          <div class="card-body">
            <h4 class="text-danger">Informasi Event</h4>

            <p><strong>Alamat :</strong><br>
            Gelora Bung Karno, Jakarta</p>

            <p><strong>Email :</strong><br>
            info@soundwavefest2025.com</p>

            <p><strong>Telepon :</strong><br>
            0812-3456-7890</p>
          </div>
        </div>
      </div>

      <div class="col-md-6 mb-4">
        <div class="card bg-dark text-white border-danger">
          <div class="card-body">
            <h4 class="text-danger">Media Sosial</h4>

            <p>Instagram : @soundwavefest2025</p>
            <p>Twitter/X : @soundwavefest</p>

            <hr class="bg-secondary">

            <h5>Jam Operasional</h5>
            <p>08.00 - 22.00 WIB</p>

            <a href="#" class="btn btn-danger btn-block">
              Hubungi Panitia
            </a>

          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<footer>
  <p>
    SOUNDWAVE FEST 2025 &copy; Hak Cipta Dilindungi |
    UTS Web Desain 2 — Paket A
  </p>
</footer>
