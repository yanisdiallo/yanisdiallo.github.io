---
layout: page
title: "Projects"
permalink: /projects/
---

<div class="projects-content">
    <div class="projects-intro">
        <p>Selected academic projects in autonomous robotics, computer vision, machine learning, product innovation and embedded systems, from Cranfield University to ECAM Lyon.</p>
        <nav class="project-jump-links" aria-label="On this page">
            <a href="#nav-yolo">NAV-YOLO</a>
            <a href="#smart-hangar">Smart Hangar</a>
            <a href="#opencv-metrology">OpenCV measurement</a>
            <a href="#robot-localisation-planning">Localisation &amp; planning</a>
            <a href="#robot-failure-classification">Failure classification</a>
            <a href="#abb-engine-assembly">ABB assembly</a>
            <a href="#cooken">Cooken</a>
            <a href="#turtlebot">TurtleBot</a>
            <a href="#wind-turbine">Wind turbine</a>
            <a href="#weather-station">Weather station</a>
            <a href="#bottle-rocket">Bottle rocket</a>
        </nav>
        <p class="project-gallery-hint">Select an image to view it at full size.</p>
    </div>

    <article class="portfolio-project" id="nav-yolo" aria-labelledby="nav-yolo-title">
        <p class="project-kicker">MSc thesis · Cranfield University · 2023</p>
        <h2 id="nav-yolo-title">NAV-YOLO: Hybrid Navigation for Obstacle Avoidance</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>ROS</span><span>Gazebo</span><span>TurtleBot3</span><span>YOLOv7</span><span>RRT</span><span>DWA</span>
        </div>
        <p>Combined YOLOv7 object detection, RRT global planning and DWA local planning to investigate obstacle avoidance for a TurtleBot3 in static and dynamic environments.</p>
        <p>Integrated visual detections into the ROS navigation pipeline by converting bounding-box information into laser-scan data.</p>
        <p>Built Gazebo scenarios and compared navigation approaches using completion time, travelled distance and collisions.</p>
        <p>Demonstrated initial operation on a physical TurtleBot3; the comparative evaluation focused on simulation after hardware issues interrupted further testing.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/nav-yolo-navigation.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Object detection integrated with navigation in simulation at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/nav-yolo-navigation.jpg' | relative_url }}" alt="YOLOv7 detections and the RRT navigation path displayed in RViz" width="1298" height="743" loading="lazy" decoding="async">
                </a>
                <figcaption>Object detection integrated with navigation in simulation</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/nav-yolo-real-robot.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Initial integration on a physical TurtleBot3 in the laboratory at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/nav-yolo-real-robot.jpg' | relative_url }}" alt="YOLO detections in a real laboratory alongside the TurtleBot navigation map in RViz" width="1371" height="658" loading="lazy" decoding="async">
                </a>
                <figcaption>Initial integration on a physical TurtleBot3 in the laboratory</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="smart-hangar" aria-labelledby="smart-hangar-title">
        <p class="project-kicker">Group research project · Cranfield University · 2023</p>
        <h2 id="smart-hangar-title">Smart Hangar: Mobile Robot Localisation</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>ROS</span><span>Sensor fusion</span><span>EKF</span><span>UWB</span><span>LiDAR</span><span>C++</span>
        </div>
        <p>Contributed to a multi-sensor localisation system for a TurtleBot3 operating in the feature-sparse DARTeC aircraft hangar. The team investigated fusion of wheel odometry, IMU, LiDAR and UWB measurements.</p>
        <p>Configured the TurtleBot3 and contributed to local and global EKF integration using the ROS robot_localization package.</p>
        <p>Measured hangar waypoints, added a ground-truth plugin to the robot URDF and contributed to simulation and physical testing.</p>
        <p>Developed a C++ LiDAR-based obstacle-avoidance simulation and contributed to the project report and presentation.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/smart-hangar-simulation.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View DARTeC hangar model used for simulation at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/smart-hangar-simulation.jpg' | relative_url }}" alt="Gazebo model of the DARTeC hangar and aircraft" width="661" height="365" loading="lazy" decoding="async">
                </a>
                <figcaption>DARTeC hangar model used for simulation</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/smart-hangar-turtlebot.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Physical testing highlighted the challenges of the hangar floor at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/smart-hangar-turtlebot.jpg' | relative_url }}" alt="TurtleBot3 negotiating an uneven section of the hangar floor" width="817" height="547" loading="lazy" decoding="async">
                </a>
                <figcaption>Physical testing highlighted the challenges of the hangar floor</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="opencv-metrology" aria-labelledby="opencv-metrology-title">
        <p class="project-kicker">Machine Vision for Robotics · Cranfield University · 2023</p>
        <h2 id="opencv-metrology-title">Real-Time Object Measurement with OpenCV</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>C++</span><span>OpenCV</span><span>Computer vision</span><span>Metrology</span>
        </div>
        <p>Built a C++ camera-based measurement system that estimates object dimensions using a reference object to establish the pixel-to-distance scale.</p>
        <p>Combined Gaussian smoothing, Canny edge detection, dilation and contour extraction to identify objects and their shapes.</p>
        <p>Used a known-size reference object for measurement calibration.</p>
        <p>Evaluated measurements at several camera heights and analysed errors and detection limitations.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/opencv-object-measurement.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Reference-based measurement of coin radii at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/opencv-object-measurement.jpg' | relative_url }}" alt="OpenCV contours and radius measurements overlaid on two coins" width="698" height="477" loading="lazy" decoding="async">
                </a>
                <figcaption>Reference-based measurement of coin radii</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/opencv-multiple-objects.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Simultaneous shape detection and measurement of multiple objects at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/opencv-multiple-objects.jpg' | relative_url }}" alt="OpenCV detection and dimension overlays on a rectangular card and two coins" width="639" height="479" loading="lazy" decoding="async">
                </a>
                <figcaption>Simultaneous shape detection and measurement of multiple objects</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="robot-localisation-planning" aria-labelledby="robot-localisation-planning-title">
        <p class="project-kicker">Autonomy in Robotic Systems · Cranfield University · 2023</p>
        <h2 id="robot-localisation-planning-title">Robot Localisation and Path Planning</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>Extended Kalman Filter (EKF)</span><span>Localisation</span><span>LiDAR</span><span>Dubins paths</span><span>RRT</span>
        </div>
        <p>Implemented and studied estimation and planning methods for autonomous robots, from landmark-based localisation to geometric and sampling-based paths.</p>
        <p>Implemented an Extended Kalman Filter using robot motion and LiDAR range/bearing measurements to six known landmarks.</p>
        <p>Constructed Dubins paths between specified poses.</p>
        <p>Completed an RRT exercise to generate routes around obstacles and visualised the resulting paths.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/rrt-path-planning.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Sampling-based path planning with RRT at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/rrt-path-planning.jpg' | relative_url }}" alt="RRT exploration tree with the resulting path highlighted" width="700" height="525" loading="lazy" decoding="async">
                </a>
                <figcaption>Sampling-based path planning with RRT</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/ekf-corrected-trajectories.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Extended Kalman Filter (EKF): comparison of six landmark-based trajectory corrections at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/ekf-corrected-trajectories.jpg' | relative_url }}" alt="Six robot trajectories corrected by the Extended Kalman Filter using individual reference landmarks" width="700" height="525" loading="lazy" decoding="async">
                </a>
                <figcaption>Extended Kalman Filter (EKF): comparison of six landmark-based trajectory corrections</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="robot-failure-classification" aria-labelledby="robot-failure-classification-title">
        <p class="project-kicker">AI and Machine Learning for Robotics · Cranfield University · 2022</p>
        <h2 id="robot-failure-classification-title">Robot Failure Classification from Force and Torque</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>Machine learning</span><span>Classification</span><span>Data analysis</span><span>Robot manipulation</span>
        </div>
        <p>Compared supervised learning approaches on five datasets describing robot manipulation outcomes through force and torque measurements.</p>
        <p>Prepared and explored labelled data for grasping, transfer, release and motion tasks.</p>
        <p>Compared classifiers including decision trees, random forests, support vector machines and k-nearest neighbours.</p>
        <p>Examined confusion matrices and classification reports, then explored model tuning and dimensionality reduction.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/robot-failure-learning-curves.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Training and validation curves used to assess model behaviour at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/robot-failure-learning-curves.jpg' | relative_url }}" alt="Training and validation score curves from the robot failure classification study" width="637" height="434" loading="lazy" decoding="async">
                </a>
                <figcaption>Training and validation curves used to assess model behaviour</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/robot-failure-classification-results.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Confusion matrices, precision, recall and F1 scores for two classifiers at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/robot-failure-classification-results.jpg' | relative_url }}" alt="Decision tree and random forest confusion matrices and classification reports" width="889" height="534" loading="lazy" decoding="async">
                </a>
                <figcaption>Confusion matrices, precision, recall and F1 scores for two classifiers</figcaption>
            </figure>
        </div>
    </article>

    <article class="portfolio-project" id="abb-engine-assembly" aria-labelledby="abb-engine-assembly-title">
        <p class="project-kicker">Fundamentals of Robotics · Cranfield University · 2022 · Group project</p>
        <h2 id="abb-engine-assembly-title">Aircraft Engine Casing Assembly with ABB RobotStudio</h2>
        <div class="project-tools" aria-label="Project technologies and areas">
            <span>ABB RobotStudio</span><span>IRB 4600</span><span>Gripper design</span><span>CAD</span><span>Robotic assembly</span>
        </div>
        <p>Worked on a group concept for assembling the upper and lower sections of an aircraft engine casing using an ABB industrial robot. The study covered component geometry, handling requirements, gripper selection and the assembly-cell sequence.</p>
        <p>The proposed solution used an internally expanding pneumatic gripper with soft contact surfaces. CAD-based mass estimates informed the selection of an ABB IRB 4600 for handling the casing sections and tooling.</p>
        <p>The cell concept transfers the lower casing to a rotating platform, places the upper section above it and uses a proposed vision-assisted alignment step to prepare the holes for fastening. The RobotStudio station below shows an early assembly setup.</p>
        <div class="project-gallery">
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/abb-engine-assembly.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Early RobotStudio assembly-cell setup at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/abb-engine-assembly.jpg' | relative_url }}" alt="RobotStudio station preview showing an ABB robot beside an engine casing and tooling" width="400" height="300" loading="lazy" decoding="async">
                </a>
                <figcaption>Early RobotStudio assembly-cell setup</figcaption>
            </figure>
            <figure class="project-figure">
                <a class="project-image-link" href="{{ '/assets/images/projects/abb-engine-casing-reference.jpg' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Target engine casing assembly supplied in the Cranfield coursework brief at full size (opens in a new tab)">
                    <img src="{{ '/assets/images/projects/abb-engine-casing-reference.jpg' | relative_url }}" alt="Reference CAD model showing the upper and lower aircraft engine casing joined at a bolted flange" width="926" height="794" loading="lazy" decoding="async">
                </a>
                <figcaption>Target engine casing assembly supplied in the Cranfield coursework brief</figcaption>
            </figure>
        </div>
    </article>

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
