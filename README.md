
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Network Engineer Portfolio">
    <title>Network Engineer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>John Doe</h1>
            <p>Network Engineer | Automation Enthusiast | Problem Solver</p>
        </div>
    </header>

    <section id="about" class="container">
        <h2>About Me</h2>
        <p>I am a network engineer with a strong background in configuring, optimizing, and securing networks. Passionate about network automation, cloud services, and troubleshooting complex network issues.</p>
    </section>

    <section id="skills" class="container">
        <h2>Skills</h2>
        <ul>
            <li>Routing & Switching (Cisco, Juniper)</li>
            <li>Network Automation (Python, Ansible)</li>
            <li>Network Security (Firewalls, VPNs, IDS/IPS)</li>
            <li>Protocols: OSPF, BGP, EIGRP, VLANs, IP Subnetting</li>
            <li>Tools: Wireshark, GNS3, Cisco Packet Tracer, SolarWinds</li>
        </ul>
    </section>

    <section id="certifications" class="container">
        <h2>Certifications</h2>
        <ul>
            <li>CCNA (Cisco Certified Network Associate)</li>
            <li>CCNP (Cisco Certified Network Professional)</li>
            <li>CompTIA Network+</li>
            <li>Certified Ethical Hacker (CEH)</li>
        </ul>
    </section>

    <section id="projects" class="container">
        <h2>Projects</h2>
        <p>Here are some examples of my work:</p>
        <ul>
            <li><a href="https://github.com/johndoe/network-automation" target="_blank">Network Automation with Python</a> - Automated network configuration and monitoring tasks using Python and Netmiko.</li>
            <li><a href="https://github.com/johndoe/packet-tracer-projects" target="_blank">Cisco Packet Tracer Network Designs</a> - A repository of various network topologies and simulations.</li>
        </ul>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>If you'd like to discuss opportunities or need help with network design, feel free to reach out!</p>
        <ul>
            <li>Email: johndoe@example.com</li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/johndoe" target="_blank">linkedin.com/in/johndoe</a></li>
            <li>GitHub: <a href="https://github.com/johndoe" target="_blank">github.com/johndoe</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 John Doe | Network Engineer</p>
    </footer>
</body>[Uploading styles.css…]()

</html>



[Uploading styles.css…]()
/* Basic reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and fonts */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header Section */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 3em;
}

header p {
    font-size: 1.2em;
}

/* Container */
.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

/* Section styling */
section {
    padding: 40px 0;
    background-color: white;
    margin-bottom: 20px;
    border-radius: 8px;
}

section h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

section ul {
    list-style-type: none;
    padding: 0;
}

section ul li {
    padding: 5px 0;
}

section ul li a {
    color: #4CAF50;
    text-decoration: none;
}

section ul li a:hover {
    text-decoration: underline;
}

/* Footer Section */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
    .container {
        width: 90%;
    }
}


