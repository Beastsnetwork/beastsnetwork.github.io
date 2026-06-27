<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beastsnetwork - Private, Secure, Untraceable Digital Currency</title>
    <style>
        :root {
            --primary-color: #ff6600;
            --secondary-color: #2c3e50;
            --light-color: #ecf0f1;
            --dark-color: #1a252f;
            --text-color: #333;
            --link-color: #3498db;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: #f9f9f9;
        }

        header {
            background-color: var(--dark-color);
            color: white;
            padding: 2rem 0;
            text-align: center;
            border-bottom: 5px solid var(--primary-color);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        h1, h2, h3 {
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        h2 {
            font-size: 1.8rem;
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 0.5rem;
            margin-top: 2rem;
        }

        p {
            margin-bottom: 1rem;
        }

        a {
            color: var(--link-color);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .copyright {
            font-style: italic;
            color: #aaa;
            text-align: center;
            margin-top: 1rem;
        }

        nav {
            background-color: var(--secondary-color);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            flex-wrap: wrap;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: white;
            font-weight: 500;
        }

        nav a:hover {
            color: var(--primary-color);
        }

        .section {
            padding: 2rem 0;
        }

        .resource-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }

        .resource-item {
            background: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .resource-item h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }

        .pgp-key {
            background: #f5f5f5;
            padding: 1rem;
            border-radius: 5px;
            font-family: monospace;
            white-space: pre-wrap;
            word-break: break-all;
            overflow-x: auto;
            margin-top: 1rem;
        }

        .note {
            background: #fff8e1;
            padding: 1rem;
            border-left: 4px solid var(--primary-color);
            margin-top: 1rem;
            font-style: italic;
        }

        .coverage-table {
            width: 100%;
            margin: 1rem 0;
            border-collapse: collapse;
        }

        .coverage-table th, .coverage-table td {
            padding: 0.75rem;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        .coverage-table th {
            background-color: var(--secondary-color);
            color: white;
        }

        .coverage-table tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav li {
                margin: 5px 0;
            }

            .resource-list {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Beastsnetwork</h1>
            <p class="copyright">Copyright (c) 2014-2024, The Beastsnetwork Project<br>
            Portions Copyright (c) 2012-2013 The Cryptonote developers.</p>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#development-resources">Development Resources</a></li>
                <li><a href="#vulnerability-response">Vulnerability Response</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#announcements">Announcements</a></li>
                <li><a href="#translations">Translations</a></li>
                <li><a href="#coverage">Coverage</a></li>
                <li><a href="#introduction">Introduction</a></li>
                <li><a href="#about-this-project">About This Project</a></li>
                <li><a href="#license">License</a></li>
                <li><a href="#contributing">Contributing</a></li>
                <li><a href="#pgp-session">PGP Session</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section id="development-resources" class="section">
            <h2>Development Resources</h2>
            <div class="resource-list">
                <div class="resource-item">
                    <h3>Web</h3>
                    <p><a href="https://beastsnetwork.win">beastsnetwork.win</a></p>
                </div>
                <div class="resource-item">
                    <h3>Mail</h3>
                    <p><a href="mailto:psychostarship@pm.me">psychostarship@pm.me</a></p>
                </div>
                <div class="resource-item">
                    <h3>GitHub</h3>
                    <p><a href="https://github.com/Beastsnetwork/beastsnetwork">github.com/Beastsnetwork/beastsnetwork</a></p>
                </div>
                <div class="resource-item">
                    <h3>IRC</h3>
                    <p><a href="https://web.libera.chat/#beastsnetwork-dev">#beastsnetwork-dev on Libera</a></p>
                </div>
            </div>
            <p>It is HIGHLY recommended that you join the <code>#beastsnetwork-dev</code> IRC channel if you are developing software that uses Beastsnetwork. Due to the nature of this open-source software project, joining this channel and idling is the best way to stay updated on best practices and new developments in the Beastsnetwork ecosystem. All you need to do is join the IRC channel and idle to stay updated with the latest in Beastsnetwork development. If you do not, you risk wasting resources on developing integrations that are not compatible with the Beastsnetwork network. The Beastsnetwork core team and community continuously make efforts to communicate updates, developments, and documentation via other platforms — but for the best information, you need to talk to other Beastsnetwork developers, and they are on IRC. <code>#beastsnetwork-dev</code> is about Beastsnetwork development, not getting help about using Beastsnetwork, or help about development of other software, including yours, unless it also pertains to Beastsnetwork code itself. For these cases, check out <code>#beastsnetwork</code>.</p>
        </section>

        <section id="vulnerability-response" class="section">
            <h2>Vulnerability Response</h2>
            <ul>
                <li>Our <a href="https://github.com/Beastsnetwork/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md">Vulnerability Response Process</a> encourages responsible disclosure.</li>
                <li>We are also available via <a href="https://hackerone.com/beastsnetwork">HackerOne</a>.</li>
            </ul>
        </section>

        <section id="research" class="section">
            <h2>Research</h2>
            <p>The <a href="https://src.beastsnetwork.win/resources/research-lab/">Beastsnetwork Research Lab</a> is an open forum where the community coordinates research into Beastsnetwork cryptography, protocols, fungibility, analysis, and more. We welcome collaboration and contributions from outside researchers! Because not all Lab work and publications are distributed as traditional preprints or articles, they may be easy to miss if you are conducting literature reviews for your own Beastsnetwork research. You are encouraged to get in touch with the Beastsnetwork research community if you have questions, wish to collaborate, or would like guidance to help avoid unnecessarily duplicating earlier or known work.</p>
            <p>The Beastsnetwork research community is available on IRC in <a href="https://web.libera.chat/#beastsnetwork-research-lab">#beastsnetwork-research-lab on Libera</a>, which is also accessible via Matrix.</p>
        </section>

        <section id="announcements" class="section">
            <h2>Announcements</h2>
            <p>You can subscribe to an <a href="https://lists.beastsnetwork.win">announcement listserv</a> to get critical announcements from the Beastsnetwork core team. The announcement list can be very helpful for knowing when software updates are needed.</p>
        </section>

        <section id="translations" class="section">
            <h2>Translations</h2>
            <p>The CLI wallet is available in different languages. If you want to help translate it, see our self-hosted localization platform, Weblate, on <a href="https://translate.beastsnetwork.win/projects/beastsnetwork/cli-wallet/">translate.beastsnetwork.win</a>. Every translation <em>must</em> be uploaded on the platform. Pull requests directly editing the code in this repository will be closed. If you need help with Weblate, you can find a guide with screenshots <a href="https://github.com/beastsnetwork-ecosystem/beastsnetwork-translations/blob/master/weblate.md">here</a>.</p>
            <p>If you need help/support/info about translations, contact the localization workgroup. You can find the complete list of contacts on the repository of the workgroup: <a href="https://github.com/beastsnetwork-ecosystem/beastsnetwork-translations#contacts">beastsnetwork-translations</a>.</p>
        </section>

        <section id="coverage" class="section">
            <h2>Coverage</h2>
            <table class="coverage-table">
                <tr>
                    <th>Type</th>
                    <th>Status</th>
                </tr>
                <tr>
                    <td>Coverity</td>
                    <td><a href="https://scan.coverity.com/projects/9657/"><img src="https://scan.coverity.com/projects/9657/badge.svg" alt="Coverity Status"></a></td>
                </tr>
                <tr>
                    <td>OSS Fuzz</td>
                    <td><a href="https://bugs.chromium.org/p/oss-fuzz/issues/list?sort=-opened&can=1&q=proj:beastsnetwork"><img src="https://oss-fuzz-build-logs.storage.googleapis.com/badges/beastsnetwork.svg" alt="Fuzzing Status"></a></td>
                </tr>
                <tr>
                    <td>Coveralls</td>
                    <td><a href="https://coveralls.io/github/Beastsnetwork/beastsnetwork?branch=master"><img src="https://coveralls.io/repos/github/Beastsnetwork/beastsnetwork/badge.svg?branch=master" alt="Coveralls Status"></a></td>
                </tr>
                <tr>
                    <td>License</td>
                    <td><a href="https://opensource.org/licenses/BSD-3-Clause"><img src="https://img.shields.io/badge/license-BSD3-blue.svg" alt="License"></a></td>
                </tr>
            </table>
        </section>

        <section id="introduction" class="section">
            <h2>Introduction</h2>
            <p>Beastsnetwork is a private, secure, untraceable, decentralized digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.</p>

            <h3>Privacy</h3>
            <p>Beastsnetwork uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain private by default.</p>

            <h3>Security</h3>
            <p>Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25-word mnemonic seed that is only displayed once and can be written down to back up the wallet. Wallet files should be encrypted with a strong passphrase to ensure they are useless if ever stolen.</p>

            <h3>Untraceability</h3>
            <p>By taking advantage of ring signatures, a special property of a certain type of cryptography, Beastsnetwork is able to ensure that transactions are not only untraceable but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.</p>

            <h3>Decentralization</h3>
            <p>The utility of Beastsnetwork depends on its decentralized peer-to-peer consensus network. Anyone should be able to run the Beastsnetwork software, validate the integrity of the blockchain, and participate in all aspects of the Beastsnetwork network using consumer-grade commodity hardware. Decentralization of the Beastsnetwork network is maintained by software development that minimizes the costs of running the Beastsnetwork software and inhibits the proliferation of specialized, non-commodity hardware.</p>
        </section>

        <section id="about-this-project" class="section">
            <h2>About This Project</h2>
            <p>This is the core implementation of Beastsnetwork. It is open-source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of Beastsnetwork that uses the protocol and network in a compatible manner.</p>
            <p>As with many development projects, the repository on GitHub is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.</p>
            <p><strong>Anyone is welcome to contribute to Beastsnetwork's codebase!</strong> If you have a fix or code change, feel free to submit it as a pull request directly to the <code>master</code> branch. In cases where the change is relatively small or does not affect other parts of the codebase, it may be merged in immediately by any one of the collaborators. On the other hand, if the change is particularly large or complex, it is expected that it will be discussed at length either well in advance of the pull request being submitted or even directly on the pull request.</p>
        </section>

        <section id="license" class="section">
            <h2>License</h2>
            <p>See <a href="LICENSE">LICENSE</a>.</p>
        </section>

        <section id="contributing" class="section">
            <h2>Contributing</h2>
            <p>If you want to help out, see <a href="docs/CONTRIBUTING.md">CONTRIBUTING</a> for a set of guidelines.</p>
        </section>

        <section id="pgp-session" class="section">
            <h2>PGP Session</h2>
            <p>For secure communication, you can use PGP to encrypt your messages. Contact us via email at <a href="mailto:psychostarship@pm.me">psychostarship@pm.me</a> for PGP-related inquiries or to obtain our public key. This ensures end-to-end encryption for sensitive discussions or vulnerability disclosures.</p>

            <h3>PGP Public Key:</h3>
            <div class="pgp-key">
-----BEGIN PGP PUBLIC KEY BLOCK-----

xYYEaK8eChYJKwYBBAHaRw8BAQdAtrZUZlwnvdhurpIN62hyByd/nE6G/MPr
M0A15e5Ni8b+CQMIBNE6HL67veVgAAAAAAAAAAAAAAAAAAAAAHDqimQ2y19Y
bMXNl0UmylbRyZys66xv4KgKGV6KZNmXcUkdDi8p8T5Y1v1qXHCborBfHjoh
rs0rcHN5Y2hvc3RhcnNoaXBAcG0ubWUgPHBzeWNob3N0YXJzaGlwQHBtLm1l
PsLAEQQTFgoAgwWCaK8eCgMLCQcJkJ6yMqcN654+RRQAAAAAABwAIHNhbHRA
bm90YXRpb25zLm9wZW5wZ3Bqcy5vcmfLJ1sonNGf/xGzu4/JyRKh5P5keIpD
c9tXe4UTeqCRFwMVCggEFgACAQIZAQKbAwIeARYhBDdcsha+kIpIVlJpK56y
MqcN654+AAA4kAEAq+W6GuHIXbd5+cR7yFaqVOITTqp1i9q9JtrQ1wquGYcA
/juLLYP60qhxZOZemKu/OUluQTr/ZjT/gp9cRekNwF8Bx4sEaK8eChIKKwYB
BAGXVQEFAQEHQNvS0jCBF0UtwWBekGu9hFaHdZBD9a7aQr/Qz3Bc9W5mAwEI
B/4JAwjMlPXCHXn9wmAAAAAAAAAAAAAAAAAAAAAAox8af2Vdsn0mUFD3K1CH
2OXpxPxgo0WMNbkBJ9tkh2n6dcO5LuweR0ANP8kg5HjbIU0H7LCewr4EGBYK
AHAFgmivHgoJkJ6yMqcN654+RRQAAAAAABwAIHNhbHRAbm90YXRpb25zLm9w
ZW5wZ3Bqcy5vcmdb4O0Ir3qEPrzhCDadlvvP9HGwRGmJFvA/2MjvZfnD1wKb
DBYhBDdcsha+kIpIVlJpK56yMqcN654+AACHqgEA3m6HJ46nh738p51YA4Ps
K2YaIxxoMoHnez8YAv5DFFEA/ikefHkcBcOvpnw9jHTGAFbyS8QuvTTms2pU
+T6MeagG
=Yw1y
-----END PGP PUBLIC KEY BLOCK-----
            </div>
            <div class="note">
                <strong>Note:</strong> The key above is a <strong>public key</strong> for encryption. Do not share your private key.
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2014-2024 The Beastsnetwork Project | Portions Copyright (c) 2012-2013 The Cryptonote developers</p>
        </div>
    </footer>
</body>
</html>
