<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WiFi Network Topology</title>
    <script defer src="https://cdn.jsdelivr.net/npm/react/umd/react.production.min.js"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/react-dom/umd/react-dom.production.min.js"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/babel-standalone/babel.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
</head>
<body class="bg-gray-100 p-6">
    <div id="root"></div>
    <script type="text/babel">
        function WifiTopologyView() {
            const [showDevices, setShowDevices] = React.useState(false);
            React.useEffect(() => {
                mermaid.initialize({ startOnLoad: true });
            }, []);

            return (
                <div className="max-w-2xl mx-auto bg-white p-6 rounded-lg shadow-lg">
                    <h1 className="text-xl font-bold mb-4">Home WiFi Network Topology</h1>
                    <div className="mb-6">
                        <div className="border rounded-lg p-4">
                            <div className="mermaid">
                                fetch('/mnt/data/diagram.mmd')
                                    .then(response => response.text())
                                    .then(data => {
                                        document.querySelector('.mermaid').innerHTML = data;
                                        mermaid.init(undefined, ".mermaid");
                                    });
                            </div>
                        </div>
                    </div>
                    <div className="mb-4">
                        <button className="flex items-center font-bold text-blue-600" onClick={() => setShowDevices(!showDevices)}>
                            {showDevices ? "▼" : "▶"} <span className="ml-2">Your Current Connected Devices</span>
                        </button>
                    </div>
                    {showDevices && (
                        <table className="w-full border-collapse border border-gray-300">
                            <thead>
                                <tr className="bg-gray-100">
                                    <th className="border p-2">Device Name</th>
                                    <th className="border p-2">Connection Type</th>
                                    <th className="border p-2">Signal Strength</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr className="border"><td className="border p-2">Ross-iPhone</td><td className="border p-2">Wi-Fi</td><td className="border p-2">98</td></tr>
                                <tr className="border"><td className="border p-2">SonosZP</td><td className="border p-2">Wi-Fi</td><td className="border p-2">184</td></tr>
                                <tr className="border"><td className="border p-2">SonosZP-3</td><td className="border p-2">Wi-Fi</td><td className="border p-2">64</td></tr>
                                <tr className="border"><td className="border p-2">Samsung</td><td className="border p-2">Wi-Fi</td><td className="border p-2">84</td></tr>
                            </tbody>
                        </table>
                    )}
                    <div className="mt-6 p-4 border-t">
                        <p>If you're still having issues, please visit our knowledge base.</p>
                        <p className="mt-2 font-bold">Would you like to speak to our support team?</p>
                        <ul className="mt-2">
                            <li><button className="w-full bg-blue-500 text-white p-2 rounded mt-2">Start a New Chat</button></li>
                            <li><button className="w-full bg-blue-500 text-white p-2 rounded mt-2">Create a Support Ticket</button></li>
                            <li className="mt-2">Call: <strong>624624</strong></li>
                            <li className="mt-2">WhatsApp Support</li>
                        </ul>
                    </div>
                </div>
            );
        }
        ReactDOM.render(<WifiTopologyView />, document.getElementById("root"));
    </script>
</body>
</html>
