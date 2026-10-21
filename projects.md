---
layout: page
title: "Projects"
permalink: /projects/
---

<div class="projects-content">
    <div class="projects-intro">
        <p>Selected academic projects in robotics, product innovation, mechanical design and embedded systems, from the most recent to the earliest.</p>
        <nav class="project-jump-links" aria-label="On this page">
            <a href="#cooken">Cooken</a>
            <a href="#turtlebot">TurtleBot</a>
            <a href="#wind-turbine">Wind turbine</a>
            <a href="#weather-station">Weather station</a>
            <a href="#bottle-rocket">Bottle rocket</a>
        </nav>
        <p class="project-gallery-hint">Select an image to view it at full size.</p>
    </div>

    <article class="portfolio-project" id="cooken" aria-labelledby="cooken-title">
        <p class="project-kicker"><time datetime="2021-09">September 2021</time> – <time datetime="2022-05">May 2022</time> · Innovation project · Team of seven</p>
        <h2 id="cooken-title">Cooken: Cordless Heated Lunchbox</h2>
        <div class="project-tools" aria-label="Project areas">
            <span>Product design</span><span>CAD</span><span>Market analysis</span>
        </div>
        <p>Worked in a multidisciplinary team of seven at ECAM Lyon on Cooken, a battery-powered lunchbox concept designed to heat meals without a power socket. The team brought together robotics, energy, mechanical engineering and supply chain backgrounds.</p>
        <p>The project combined user-needs analysis, competitor research and product design with a business model and go-to-market strategy. Following technical feedback, the concept was refocused on portable heating. The proposal included CAD renders of the assembled product and its internal components.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/cooken-lunchbox.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the Cooken lunchbox CAD render at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/cooken-lunchbox.jpg' | relative_url }}" alt="CAD render of the assembled Cooken lunchbox with its lid closed" width="1564" height="757" loading="lazy" decoding="async">
                </a>
                <figcaption>Assembled lunchbox concept</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/cooken-exploded-view.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the Cooken lunchbox exploded view at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/cooken-exploded-view.jpg' | relative_url }}" alt="Exploded CAD view showing the Cooken lunchbox lid, food container, heating and electronics layers, battery pack and outer casing" width="626" height="693" loading="lazy" decoding="async">
                </a>
                <figcaption>Exploded view of the product components</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="turtlebot" aria-labelledby="turtlebot-title">
        <p class="project-kicker"><time datetime="2021">2021</time> · Robotics · Individual project</p>
        <h2 id="turtlebot-title">TurtleBot Mapping &amp; Obstacle Avoidance</h2>
        <div class="project-tools" aria-label="Tools used">
            <span>ROS</span><span>TurtleBot</span><span>catkin</span>
        </div>
        <p>Set up the ROS environment and TurtleBot, and created a package in a catkin workspace. Programmed the robot to map its surroundings while avoiding obstacles, turning by a random angle when an object was detected in its path.</p>
        <p>The project produced a map of the explored environment, shown alongside the original test environment below.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/turtlebot-environment.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the TurtleBot test environment at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/turtlebot-environment.jpg' | relative_url }}" alt="Simulated indoor environment used for the TurtleBot mapping project" width="347" height="285" loading="lazy" decoding="async">
                </a>
                <figcaption>Environment to be mapped</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/turtlebot-map.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the resulting TurtleBot map at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/turtlebot-map.jpg' | relative_url }}" alt="Occupancy map produced during the TurtleBot exploration" width="364" height="246" loading="lazy" decoding="async">
                </a>
                <figcaption>Mapping result</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="wind-turbine" aria-labelledby="wind-turbine-title">
        <p class="project-kicker"><time datetime="2021">2021</time> · Mechanical design · Team of three</p>
        <h2 id="wind-turbine-title">Wind Turbine Design &amp; Blade Optimisation</h2>
        <div class="project-tools" aria-label="Tools used">
            <span>PTC Creo</span><span>GNU Octave</span><span>CAD</span>
        </div>
        <p>Created and assembled a wind turbine model in PTC Creo. Developed Octave code to calculate turbine parameters, including torque, power, blade chord and angle of attack, with and without wake rotation.</p>
        <p>Used the numerical results to redesign the blades and update their geometry.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/wind-turbine-initial.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the initial wind turbine CAD model at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/wind-turbine-initial.jpg' | relative_url }}" alt="Initial three-bladed wind turbine assembly modelled in PTC Creo" width="380" height="323" loading="lazy" decoding="async">
                </a>
                <figcaption>Initial turbine design</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/wind-turbine-redesigned.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the redesigned wind turbine blades at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/wind-turbine-redesigned.jpg' | relative_url }}" alt="Revised wind turbine blades with a narrower, tapered geometry" width="351" height="287" loading="lazy" decoding="async">
                </a>
                <figcaption>Blade redesign informed by the calculations</figcaption>
            </figure>
        </div>
        <details class="project-details">
            <summary>View the calculation plots</summary>
            <figure class="project-figure">
                <a class="project-image-link project-image-link-wide" href="{{ '/assets/images/projects/wind-turbine-calculations.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the Octave calculation plots at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/wind-turbine-calculations.jpg' | relative_url }}" alt="Octave workspace and plots from the wind turbine parameter calculations" width="755" height="428" loading="lazy" decoding="async">
                </a>
                <figcaption>Numerical results used in the blade design process</figcaption>
            </figure>
        </details>
    </article>

    <article class="portfolio-project" id="weather-station" aria-labelledby="weather-station-title">
        <p class="project-kicker"><time datetime="2020">2020</time> · Embedded systems · Team of three</p>
        <h2 id="weather-station-title">Weather Station: Wind Speed &amp; Direction</h2>
        <div class="project-tools" aria-label="Tools used">
            <span>Arduino</span><span>PTC Creo</span><span>CAD</span>
        </div>
        <p>Designed the weather station components and assembly in PTC Creo, including the wind-direction connector. Wrote Arduino code to measure wind speed and direction.</p>
        <p>The measurement code was tested on a physical weather station, connecting the mechanical design work with embedded sensing.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/weather-station-assembly.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the weather station assembly at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/weather-station-assembly.jpg' | relative_url }}" alt="Weather station CAD assembly with a wind vane and a cup anemometer" width="923" height="360" loading="lazy" decoding="async">
                </a>
                <figcaption>Complete weather station assembly</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/weather-station-drawing.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the wind-direction connector drawing at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/weather-station-drawing.jpg' | relative_url }}" alt="Technical drawing showing the wind-direction connector in several views" width="500" height="366" loading="lazy" decoding="async">
                </a>
                <figcaption>Wind-direction connector drawing</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="bottle-rocket" aria-labelledby="bottle-rocket-title">
        <p class="project-kicker"><time datetime="2020">2020</time> · Modelling &amp; simulation · Team of three</p>
        <h2 id="bottle-rocket-title">Bottle Rocket: Design &amp; Aerodynamic Simulation</h2>
        <div class="project-tools" aria-label="Tools used">
            <span>PTC Creo</span><span>Arduino</span><span>ANSYS</span>
        </div>
        <p>Modelled a bottle rocket in PTC Creo and calculated launch parameters for a target range of 15 metres. Wrote Arduino code using two switches to record the rocket's passage times and estimate its speed.</p>
        <p>Simulated airflow around the rocket in ANSYS to study its aerodynamic behaviour. The planned launch tests could not take place because of the COVID-19 pandemic.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/bottle-rocket-cad.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the bottle rocket CAD model at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/bottle-rocket-cad.jpg' | relative_url }}" alt="Bottle rocket CAD model with a nose cone and fins" width="345" height="156" loading="lazy" decoding="async">
                </a>
                <figcaption>Bottle rocket model in PTC Creo</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/bottle-rocket-airflow.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View the rocket airflow simulation at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/bottle-rocket-airflow.jpg' | relative_url }}" alt="ANSYS airflow pathlines around the rocket, coloured by velocity magnitude" width="454" height="262" loading="lazy" decoding="async">
                </a>
                <figcaption>Airflow simulation in ANSYS</figcaption>
            </figure>
        </div>
    </article>
</div>
