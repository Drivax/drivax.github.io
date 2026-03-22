<section id="about-me" class="about-hero">
	<div class="about-hero-copy">
		<p class="eyebrow">About me</p>
		<h1 class="title">Alexandre Lalance</h1>
		<p class="lead">Machine learning and quantitative research engineer with a strong foundation in applied mathematics, statistical modelling and end-to-end ML delivery. </p>
		<p>Today I work at Credit Agricole S.A. on regulatory modelling, after training in applied mathematics and statistics at Paris-Saclay and Sorbonne Universite. My focus is on high-value machine learning systems: predictive modelling, optimization, time-series learning, reinforcement learning and explainable workflows that stand up in production environments.</p>
		<div class="about-highlights">
			<span class="metric-pill">Climate risk and Basel models</span>
			<span class="metric-pill">Python, SQL, PyTorch, AWS</span>
			<span class="metric-pill">ML, optimization, time series</span>
			<span class="metric-pill">French native, English fluent</span>
		</div>
	</div>
</section>

<section id="experience" class="about-section-block">
	<h2 class="title">What I work on</h2>
	<div class="info-grid">
		<article class="info-card">
			<h3>Quantitative modelling</h3>
			<p>I design and review statistical and machine learning models for regulated environments, with attention to traceability, performance and business interpretation.</p>
		</article>
		<article class="info-card">
			<h3>AI systems</h3>
			<p>I am particularly interested in LLM workflows, reinforcement learning and applied deep learning systems that convert data into measurable operational value.</p>
		</article>
		<article class="info-card">
			<h3>Scientific engineering</h3>
			<p>My background spans applied mathematics, signal-rich time series and optimization, which lets me move comfortably between theory, notebooks, code and deployment-facing deliverables.</p>
		</article>
	</div>
</section>

<section id="projects" class="about-section-block">
	<h2 class="title">Featured Projects</h2>
	<p class="section-intro">A selection of ML, optimization and fun side projects built around aerospace, board games or basically anything fun to explore. Each card links to the repository and the main notebook used to explore results.</p>
	<div class="project-grid project-grid-featured">
		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://raw.githubusercontent.com/Drivax/Gym-lunar-lander/main/trajectories.png" alt="Trajectory visualization for Gym Lunar Lander" loading="lazy">
			<div class="project-card-body">
				<h3>Rocket Landing RL Simulator</h3>
				<p class="project-summary">Robust PPO agent for LunarLander under delayed actions, noisy observations and wind perturbations. The setup adds partial observability and domain randomization to force stable control policies beyond the clean benchmark.</p>
				<div class="project-metrics">
					<span class="project-tag">PPO + GAE</span>
					<span class="project-tag">3M + 1M timesteps</span>
					<span class="project-tag">Success rate &gt; 95%</span>
				</div>
				<p class="project-notes">Multi-phase training, 8 parallel environments, observation normalization and robustness evaluation under heavy delay/noise shift.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Gym-lunar-lander" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Gym-lunar-lander/blob/main/test_env.ipynb" target="_blank" rel="noreferrer">Open Notebook</a>
				</div>
			</div>
		</article>

		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://raw.githubusercontent.com/Drivax/Orbital-trajectory-predictor/main/results/trajectory_3d_snapshot.png" alt="3D orbital trajectory prediction preview" loading="lazy">
			<div class="project-card-body">
				<h3>Orbital Trajectory Prediction</h3>
				<p class="project-summary">LSTM with temporal attention trained on real TLE data and SGP4-generated trajectories to predict 5-minute orbital displacement. The pipeline combines orbital physics, feature engineering and recurrent learning.</p>
				<div class="project-metrics">
					<span class="project-tag">LSTM + Attention</span>
					<span class="project-tag">31 satellites</span>
					<span class="project-tag">RMSE 41.9 km</span>
				</div>
				<p class="project-notes">21-dimensional physics-informed features, chronological per-satellite split, residual skip connection and conjunction-aware visual analytics.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Orbital-trajectory-predictor" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Orbital-trajectory-predictor/blob/main/notebooks/04_results.ipynb" target="_blank" rel="noreferrer">Open Notebook</a>
				</div>
			</div>
		</article>

		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://raw.githubusercontent.com/Drivax/Satellite-anomaly-detection/main/results/model_comparison.png" alt="Satellite anomaly detection model comparison chart" loading="lazy">
			<div class="project-card-body">
				<h3>Satellite Telemetry Anomaly Detection</h3>
				<p class="project-summary">Unsupervised anomaly detection for satellite telemetry using Isolation Forest and a PyTorch autoencoder on OPSSAT-like multivariate time series. The system targets early fault detection before degradation becomes operationally critical.</p>
				<div class="project-metrics">
					<span class="project-tag">PyTorch + Isolation Forest</span>
					<span class="project-tag">120k points</span>
					<span class="project-tag">AUC 0.8207</span>
				</div>
				<p class="project-notes">Chronological split, rolling statistics, orbital context features, weighted reconstruction loss and Streamlit dashboard for operational monitoring.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Satellite-anomaly-detection" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Satellite-anomaly-detection/blob/main/notebooks/05_results.ipynb" target="_blank" rel="noreferrer">Open Notebook</a>
				</div>
			</div>
		</article>

		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://raw.githubusercontent.com/Drivax/Aerospace-Supply-Chain-Optimization/main/results/optimized_network.png" alt="Aerospace supply chain optimization network preview" loading="lazy">
			<div class="project-card-body">
				<h3>Aerospace Supply Chain Optimizer</h3>
				<p class="project-summary">Decision-intelligence pipeline combining delay prediction and MILP procurement optimization for critical aerospace components. The optimization balances spend, schedule robustness, risk and carbon footprint.</p>
				<div class="project-metrics">
					<span class="project-tag">GBDT + MILP</span>
					<span class="project-tag">Optimal plan</span>
					<span class="project-tag">68.74% cost reduction</span>
				</div>
				<p class="project-notes">Robust deadline constraints, scenario-based uncertainty, tunable risk/carbon weights and 100% on-time delivery in the current run summary.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Aerospace-Supply-Chain-Optimization" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Aerospace-Supply-Chain-Optimization/blob/main/notebooks/04_results.ipynb" target="_blank" rel="noreferrer">Open Notebook</a>
				</div>
			</div>
		</article>

		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://github.com/user-attachments/assets/fd0d8fa1-119e-4244-a53c-0a435f0a5e5e" alt="FlightTracker web application UI showing live flights on an interactive map" loading="lazy">
			<div class="project-card-body">
				<h3>FlightTracker</h3>
				<p class="project-summary">Web application that identifies flights overhead in real time based on your location — showing flight number, airline, speed, altitude, heading and origin country, with an interactive map and aircraft photo upload.</p>
				<div class="project-metrics">
					<span class="project-tag">Node.js + Express</span>
					<span class="project-tag">Leaflet.js</span>
					<span class="project-tag">OpenSky Network API</span>
				</div>
				<p class="project-notes">Live flight data with no API key required, configurable search radius of 50–300 km, auto-refresh every 30 seconds and responsive design for mobile and desktop.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Flight-tracking" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Flight-tracking" target="_blank" rel="noreferrer">Open Project</a>
				</div>
			</div>
		</article>

		<article class="project-card project-card-featured">
			<img class="project-card-media" src="https://raw.githubusercontent.com/Drivax/Catan/main/fine_tuning_results/best_parameters_20260320_162409.png" alt="Catan strategy optimization best parameter search visualization" loading="lazy">
			<div class="project-card-body">
				<h3>Catan Best Strategy Explorer</h3>
				<p class="project-summary">Fun side project ( in french )exploring how to find strong Catan strategies through simulation and parameter search across different gameplay policies.</p>
				<div class="project-metrics">
					<span class="project-tag">Game strategy</span>
					<span class="project-tag">Parameter search</span>
					<span class="project-tag">Simulation</span>
				</div>
				<p class="project-notes">Built as an experimental sandbox to compare setups and identify robust parameter combinations for better decision-making in Catan.</p>
				<div class="project-links">
					<a href="https://github.com/Drivax/Catan" target="_blank" rel="noreferrer">View Repository</a>
					<a href="https://github.com/Drivax/Catan" target="_blank" rel="noreferrer">Open Project</a>
				</div>
			</div>
		</article>
	</div>
</section>

<section id="contact" class="about-section-block">
	<h2 class="title">Contact</h2>
	<p class="section-intro">If you want to discuss machine learning, quantitative modelling, optimization or AI product opportunities, the fastest way is by email or LinkedIn.</p>
	<div class="contact-links">
		<a href="mailto:alex.lalance@gmail.com">Contact</a>
		<a href="https://www.linkedin.com/in/alexandre-lalance/" target="_blank" rel="noreferrer">LinkedIn</a>
		<a href="./docs/Alexandre_LALANCE_CV.pdf" target="_blank" rel="noreferrer">CV PDF</a>
		<a href="https://github.com/Drivax" target="_blank" rel="noreferrer">GitHub</a>
	</div>
</section>