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
	<p class="section-intro">A selection of machine learning and optimization projects spanning credit risk, aerospace and simulation. Explore the code, methods and measured results.</p>
	<div class="project-grid project-grid-featured">
        <article class="project-card project-card-featured credit-project-card">
            <div class="project-card-body">
                <p class="eyebrow">Credit risk / Reinforcement learning</p>
                <h3>Dynamic Credit Limit Optimization</h3>
                <p class="project-summary">A synthetic sequential-decision study showing how observable-state behavior-cloning initialization changes PPO learning and recovers state-dependent credit-limit control.</p>
                <div class="project-metrics">
                    <span class="project-tag">PPO / behavior cloning / OPE</span>
                    <span class="project-tag">150 customers / 5 seeds / 5 worlds</span>
                    <span class="project-tag">+€200.8 synthetic NEV/customer vs contraction</span>
                </div>
                <p class="project-notes">BCRegularizedPPO vs AlwaysDecrease20 at 32,768 steps: nominal gain +€200.8 (95% CI [€120.7, €293.0]); severe stress +€61.1 (95% CI [€32.8, €96.7]). Benefits are objective- and scenario-dependent; extra BC regularization does not establish a NEV gain over initialization alone.</p>
                <div class="project-links">
                    <a href="#credit-limit">Summary &amp; Results ↓</a>
                    <a href="https://github.com/Drivax/Dynamic-Credit-Limit-Optimization-with-RL-" target="_blank" rel="noreferrer">View Repository ↗</a>
                </div>
            </div>
        </article>

		<article class="project-card project-card-featured">
            <a class="project-figure-link" href="./docs/assets/constellation-spacing.png" target="_blank" rel="noreferrer" aria-label="View Constellation Manager figure at full size">
                <img class="project-card-media project-chart" src="./docs/assets/constellation-spacing.png" alt="Spacing error over eight hours: classical PD reduces error while MAPPO remains close to no control." loading="lazy" width="1492" height="948">
            </a>
            <div class="project-card-body">
                <h3>Constellation Manager</h3>
                <p class="project-summary">Satellite spacing control with physically coupled tangential impulses and a limited delta-v budget. A shared-actor MAPPO policy is compared with no control, proportional feedback and classical PD in a simplified orbital model.</p>
                <div class="project-metrics">
                    <span class="project-tag">P / PD / MAPPO</span>
                    <span class="project-tag">3 training seeds / 5 scenarios</span>
                    <span class="project-tag">100 and 1,000 satellites</span>
                </div>
                <p class="project-notes">At 100 satellites, PD achieves 2.02% mean spacing error and 100% nominal success versus 5.56% and 0% for MAPPO. MAPPO does not improve on PD under this budget; its error grows to 25.88% at 1,000 satellites without retraining.</p>
                <div class="project-links">
                    <a href="https://github.com/Drivax/Constellation-manager" target="_blank" rel="noreferrer">View Repository</a>
                    <a href="./docs/assets/constellation-spacing.png" target="_blank" rel="noreferrer">View Measured Results</a>
                </div>
            </div>
        </article>

		<article class="project-card project-card-featured">
            <a class="project-figure-link" href="./docs/assets/milkomeda-uncertainty.png" target="_blank" rel="noreferrer" aria-label="View Milkomeda figure at full size">
                <img class="project-card-media project-chart" src="./docs/assets/milkomeda-uncertainty.png" alt="Twenty simulated galaxy-center trajectories, separation percentile bands and distributions of closest approach under illustrative uncertainty." loading="lazy" width="1960" height="1420">
            </a>
            <div class="project-card-body">
                <h3>Milkomeda</h3>
                <p class="project-summary">An interactive, reproducible N-body study of the Milky Way–Andromeda interaction. Configure masses, velocities, timestep and softening, run scenarios in Streamlit, and compare their trajectories and numerical conservation.</p>
                <div class="project-metrics">
                    <span class="project-tag">Configurable N-body / Streamlit</span>
                    <span class="project-tag">25 sensitivity runs / 20 Monte Carlo</span>
                    <span class="project-tag">Energy / momentum / COM checks</span>
                </div>
                <p class="project-notes">Explicitly configured toy uncertainty produces a range of future trajectories. Particle count, initial sampling and numerical choices materially change the encounter: good energy conservation is not proof of physical convergence, and this is not a certain collision forecast.</p>
                <div class="project-links">
                    <a href="https://github.com/Drivax/Milkomeda" target="_blank" rel="noreferrer">View Repository</a>
                    <a href="./docs/assets/milkomeda-uncertainty.png" target="_blank" rel="noreferrer">View Measured Results</a>
                </div>
            </div>
        </article>

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
            <a class="project-figure-link" href="./docs/assets/orbital-error-horizon.png" target="_blank" rel="noreferrer" aria-label="View Orbital Trajectory Prediction figure at full size">
                <img class="project-card-media project-chart" src="./docs/assets/orbital-error-horizon.png" alt="Position prediction error across five forecast horizons comparing constant velocity, two-body gravity, J2, pure ML and hybrid residual learning." loading="lazy" width="1544" height="965">
            </a>
            <div class="project-card-body">
                <h3>Orbital Trajectory Prediction</h3>
                <p class="project-summary">A controlled synthetic benchmark comparing physics, pure ML and physics-plus-ML residual orbital prediction. Disjoint satellite populations test five forecast horizons from 5 minutes to 6 hours and shifts in altitude, inclination and eccentricity.</p>
                <div class="project-metrics">
                    <span class="project-tag">Two Body / J2 / residual MLP</span>
                    <span class="project-tag">3 training seeds / held-out satellites</span>
                    <span class="project-tag">5 horizons / ID and OOD</span>
                </div>
                <p class="project-notes">At 6 hours in distribution, the hybrid reduces two-body mean error from 185 km to 3.73 km; the J2 baseline is best at 0.144 km. Under distribution shift, hybrid error rises to 360 km versus 202 km for two-body physics. These are simulation results, not operational orbit predictions.</p>
                <div class="project-links">
                    <a href="https://github.com/Drivax/Orbital-trajectory-predictor" target="_blank" rel="noreferrer">View Repository</a>
                    <a href="./docs/assets/orbital-error-horizon.png" target="_blank" rel="noreferrer">View Measured Results</a>
                </div>
            </div>
        </article>

		<article class="project-card project-card-featured" id="satellite-anomalies">
            <a class="project-figure-link" href="./docs/assets/satellite-opssat-performance.png" target="_blank" rel="noreferrer" aria-label="View OPS-SAT benchmark figure at full size">
                <img class="project-card-media project-chart" src="./docs/assets/satellite-opssat-performance.png" alt="OPS-SAT results: official and chronological evaluation of Autoencoder, Isolation Forest and Robust Distance, with recall and false-positive rates" loading="lazy" width="1667" height="1017">
            </a>
            <div class="project-card-body">
                <h3>Satellite Telemetry Anomaly Detection</h3>
                <p class="project-summary">An offline anomaly-detection benchmark on real ESA OPS-SAT telemetry. Robust Distance, Isolation Forest and a PyTorch autoencoder are compared using separate normal-data calibration, the official test split and a chronological generalization test.</p>
                <div class="project-metrics">
                    <span class="project-tag">2,123 real segments / 9 channels</span>
                    <span class="project-tag">3 models / 5 seeds</span>
                    <span class="project-tag">97 tests passed</span>
                </div>
                <p class="project-notes">On the official test with all 19 descriptors, Robust Distance achieves average precision 0.829 versus 0.759 for the autoencoder. False-positive rates rise sharply on the chronological test. Reproducible pipelines, uncertainty estimates and a dashboard support review of complete annotated segments; these results do not establish early warning or operational readiness.</p>
                <div class="project-links">
                    <a href="https://github.com/Drivax/Satellite-anomaly-detection" target="_blank" rel="noreferrer">View Repository</a>
                    <a href="./docs/assets/satellite-opssat-performance.png" target="_blank" rel="noreferrer">View Measured Results</a>
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
		<a href="./docs/Alexandre_LALANCE_CV__eng_.pdf" target="_blank" rel="noreferrer">CV PDF</a>
		<a href="https://github.com/Drivax" target="_blank" rel="noreferrer">GitHub</a>
	</div>
</section>