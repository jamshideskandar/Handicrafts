
<div class="overlay">
  <h1>خوش آمدید به Eskandar Crafts</h1>
  <p>فروشگاه تخصصی صنایع‌دستی اصیل ایرانی - اصفهان</p>
</div>

body {
  margin: 0;
  padding: 0;
  font-family: "Tahoma", sans-serif;
  height: 100vh;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  background: black;
  position: relative;
}

body::before {
  content: "";
  position: absolute;
  z-index: 0;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: conic-gradient(
    from 0deg,
    #3e0e61,
    #5b1a84,
    #8140b2,
    #9b59b6,
    #8140b2,
    #5b1a84,
    #3e0e61
  );
  animation: spin 20s linear infinite;
  filter: blur(100px);
  opacity: 0.3;
}

@keyframes spin {
  to {
    transform: rotate(360deg);
  }
}

.overlay {
  position: relative;
  z-index: 1;
  background-color: rgba(0, 0, 0, 0.5);
  padding: 2rem 3rem;
  border-radius: 20px;
  box-shadow: 0 0 20px #9b59b6;
  text-align: center;
  max-width: 600px;
}

.overlay h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #fff;
}

.overlay p {
  font-size: 1.2rem;
  color: #ddd;
}
