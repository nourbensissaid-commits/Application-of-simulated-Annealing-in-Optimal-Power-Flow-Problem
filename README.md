<img src="artboard2.png" alt="Logo" style="width: 120px; display: block; margin-bottom: 20px;">

<h2>Optimal Power Flow Using Simulated Annealing</h2>

<p>
A <strong>PyQt5 application</strong> for analyzing IEEE test systems. The user selects a system, and the application calculates the <strong>bus admittance matrix</strong>, performs <strong>power flow analysis</strong>, and solves the <strong>Optimal Power Flow (OPF)</strong> problem using the <strong>Simulated Annealing</strong> algorithm.
</p>
<div style="text-align: center; margin: 30px 0;">
    <img src="9.png" alt="OPF Application" style="width: 100%; max-width: 1000px;">
    <img src="10.png" alt="OPF Application" style="width: 100%; max-width: 1000px;">
    <img src="11.png" alt="OPF Application" style="width: 100%; max-width: 1000px;">
</div>
<h2>Application Overview</h2>

<p>
The <strong>PyQt5 application</strong> provides a complete workflow for power flow analysis and Optimal Power Flow (OPF) using standard IEEE test systems.
</p>

<h3>1. Welcome Page</h3>

<p>
The application starts with a welcome page providing access to the different sections of the power system analysis.
</p>

<div style="text-align: center; margin: 20px 0;">
    <img src="A.png" alt="Welcome Page" style="width: 100%;">
</div>

<h3>2. System Selection</h3>

<p>
The user can select the desired <strong>IEEE test system</strong> to be analyzed.
</p>

<div style="text-align: center; margin: 20px 0;">
    <img src="B.png" alt="System Selection" style="width: 100%;">
</div>

<h3>3. Power Flow Analysis</h3>

<p>
The application calculates the bus admittance matrix and performs the power flow analysis using the selected method: <strong>Gauss-Seidel, Newton-Raphson, or Fast Decoupled</strong>.
</p>

<div style="text-align: center; margin: 20px 0;">
    <img src="C.png" alt="Power Flow Analysis" style="width: 100%;">
</div>

<h3>4. System Visualization</h3>

<p>
The resulting system can be visualized, including the buses and the admittance values of the lines connecting them.
</p>

<div style="text-align: center; margin: 20px 0;">
    <img src="D.png" alt="System Visualization" style="width: 100%;">
</div>

<h3>5. Optimal Power Flow</h3>

<p>
Finally, the application performs the <strong>Optimal Power Flow (OPF)</strong> using the <strong>Simulated Annealing</strong> algorithm. Other methods, such as <strong>PSO</strong> and the <strong>Lambda method</strong>, are also proposed.
</p>

<div style="text-align: center; margin: 20px 0;">
    <img src="E.png" alt="OPF Results" style="width: 100%;">
</div>
