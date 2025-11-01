<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Immanuel Mbugua - Cloud/DevOps Profile</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Inter Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Apply Inter font and clean background */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #eef2ff; /* Light indigo background */
        }
        /* Custom list style for expertise */
        .custom-list li {
            padding-left: 1.5rem;
            position: relative;
            margin-bottom: 0.5rem;
        }
        .custom-list li::before {
            content: '☁️'; /* Cloud emoji or use a checkmark icon */
            position: absolute;
            left: 0;
            color: #4f46e5;
            font-size: 1.1rem;
        }
    </style>
</head>
<body class="min-h-screen p-4 sm:p-8 flex justify-center items-start">

    <!-- Main Profile Container -->
    <div class="w-full max-w-4xl bg-white p-6 md:p-10 rounded-2xl shadow-2xl space-y-8">

        <!-- Header & Introduction -->
        <header class="text-center pb-4 border-b border-indigo-100">
            <p class="text-lg font-medium text-gray-600 mb-2">Hi there! 👋 Welcome to my Cloud - Dev Profile!</p>
            <h1 class="text-4xl md:text-5xl font-extrabold text-gray-900 mb-4 leading-tight">
                Immanuel Mbugua
            </h1>
            <p class="text-xl text-indigo-700 font-semibold mb-6">
                2x AWS Certified Professional & Aspiring Cloud/DevOps Engineer
            </p>
            <p class="text-gray-700 max-w-2xl mx-auto">
                My passion lies in **bridging the gap** between robust, scalable cloud architecture and efficient software development. I specialize in building **resilient applications** and optimizing deployment pipelines using automation.
            </p>
        </header>

        <!-- About My Journey -->
        <section class="bg-indigo-50 p-6 rounded-xl shadow-md">
            <h2 class="text-2xl font-bold text-indigo-800 mb-4 flex items-center">
                <span class="mr-2">🚀</span> About My Journey
            </h2>
            <p class="text-gray-700 mb-6">
                I am a detail-oriented problem-solver with proven hands-on experience in complex technical environments. My journey accelerated when I was selected as one of only **15 interns from over 3,000 applicants** for the inaugural AWS Kenya Cloud Support Engineer Internship.
            </p>
            
            <h3 class="text-xl font-semibold text-gray-800 mb-3">My key areas of expertise include:</h3>
            <ul class="custom-list space-y-3 pl-0">
                <li>
                    <strong class="font-bold text-indigo-700">Cloud Architecture:</strong> Designing and managing infrastructure using AWS Core Services (EC2, Lambda, VPC, RDS, S3) guided by my AWS Solutions Architect - Associate certification.
                </li>
                <li>
                    <strong class="font-bold text-indigo-700">Automation:</strong> Developing JS (IaC) scripts to streamline support workflows, automate infrastructure tasks, and enhance system reliability.
                </li>
                <li>
                    <strong class="font-bold text-indigo-700">Full-Stack Capability:</strong> Proficient in creating enterprise-grade applications using React on the frontend and Node.js, and PostgreSQL (PERN) on the backend.
                </li>
                <li>
                    <strong class="font-bold text-indigo-700">DevOps Focus:</strong> Leveraging Docker and Kubernetes principles for containerization, and integrating CI/CD practices to ensure fast, reliable deployments.
                </li>
            </ul>
        </section>

        <!-- Certifications Table -->
        <section>
            <h2 class="text-3xl font-bold text-gray-800 mb-5 flex items-center">
                <span class="mr-2">🏆</span> Certifications
            </h2>
            <div class="overflow-x-auto rounded-xl shadow-lg border border-gray-200">
                <table class="min-w-full divide-y divide-gray-200">
                    <thead class="bg-indigo-600">
                        <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-white uppercase tracking-wider">Certification</th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-white uppercase tracking-wider">Status</th>
                            <th scope="col" class="px-6 py-3 text-center text-xs font-semibold text-white uppercase tracking-wider">Verification (Credly)</th>
                        </tr>
                    </thead>
                    <tbody class="bg-white divide-y divide-gray-200">
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">AWS Certified Solutions Architect - Associate (SAA)</td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-green-600 font-semibold">Certified</td>
                            <td class="px-6 py-4 whitespace-nowrap text-center text-sm">
                                <a href="https://www.credly.com/users/mbugua-immanuel" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium transition duration-150">View Badge</a>
                            </td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">AWS Certified Cloud Practitioner (CCP)</td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-green-600 font-semibold">Certified</td>
                            <td class="px-6 py-4 whitespace-nowrap text-center text-sm">
                                <a href="https://www.credly.com/users/mbugua-immanuel" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium transition duration-150">View Badge</a>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Technical Toolkit -->
        <section>
            <h2 class="text-3xl font-bold text-gray-800 mb-5 flex items-center">
                <span class="mr-2">🛠️</span> My Technical Toolkit
            </h2>

            <!-- Cloud & DevOps Table -->
            <h3 class="text-xl font-bold text-gray-700 mt-6 mb-3">Cloud & DevOps</h3>
            <div class="overflow-x-auto rounded-xl shadow-lg border border-gray-200 mb-8">
                <table class="min-w-full divide-y divide-gray-200">
                    <thead class="bg-gray-100">
                        <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-1/3">Category</th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-2/3">Technologies</th>
                        </tr>
                    </thead>
                    <tbody class="bg-white divide-y divide-gray-200">
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">AWS Core Services</td>
                            <td class="px-6 py-4 text-sm text-gray-700">EC2, S3, VPC, RDS, Lambda, IAM, CloudWatch, DynamoDB</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">DevOps Tools</td>
                            <td class="px-6 py-4 text-sm text-gray-700">Docker, Kubernetes, CI/CD, Git, Agile</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Cloud Concepts</td>
                            <td class="px-6 py-4 text-sm text-gray-700">IaaS, PaaS, SaaS, IaC, Public/Private/Hybrid Cloud</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Programming & Web Table -->
            <h3 class="text-xl font-bold text-gray-700 mb-3">Programming & Web</h3>
            <div class="overflow-x-auto rounded-xl shadow-lg border border-gray-200">
                <table class="min-w-full divide-y divide-gray-200">
                    <thead class="bg-gray-100">
                        <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-1/3">Category</th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-2/3">Technologies</th>
                        </tr>
                    </thead>
                    <tbody class="bg-white divide-y divide-gray-200">
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Languages</td>
                            <td class="px-6 py-4 text-sm text-gray-700">JavaScript, Python (from CV)</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Frameworks</td>
                            <td class="px-6 py-4 text-sm text-gray-700">React, Node.js</td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Databases</td>
                            <td class="px-6 py-4 text-sm text-gray-700">MySQL, PostgreSQL</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>
        
        <!-- Get in Touch -->
        <section class="pt-4 border-t border-indigo-100">
            <h2 class="text-3xl font-bold text-gray-800 mb-5 flex items-center">
                <span class="mr-2">📬</span> Get in Touch
            </h2>
            <p class="text-gray-700 mb-6">
                Feel free to explore my repositories and projects that showcase my cloud, automation, and full-stack work. I'm always open to discussing new opportunities or collaborating on impactful solutions!
            </p>
            
            <div class="overflow-x-auto rounded-xl shadow-lg border border-gray-200">
                <table class="min-w-full divide-y divide-gray-200">
                    <thead class="bg-gray-100">
                        <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-1/4">Platform</th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-semibold text-gray-600 uppercase tracking-wider w-3/4">Link</th>
                        </tr>
                    </thead>
                    <tbody class="bg-white divide-y divide-gray-200">
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">GitHub</td>
                            <td class="px-6 py-4 text-sm">
                                <a href="https://github.com/techreborn001" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition duration-150">github.com/techreborn001</a>
                            </td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Credly</td>
                            <td class="px-6 py-4 text-sm">
                                <a href="https://www.credly.com/users/mbugua-immanuel" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition duration-150">credly.com/users/mbugua-immanuel</a>
                            </td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">LinkedIn</td>
                            <td class="px-6 py-4 text-sm">
                                <a href="https://www.linkedin.com/in/immanuel-mbugua-02766a2b8" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition duration-150">www.linkedin.com/in/immanuel-mbugua-02766a2b8</a>
                            </td>
                        </tr>
                        <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">Email</td>
                            <td class="px-6 py-4 text-sm text-gray-700">Immanuel.Mbugua@gmail.com</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            
            <p class="text-center text-xl font-bold text-indigo-700 mt-8">Together let’s innovate the future!!</p>
        </section>

    </div>

</body>
</html>
