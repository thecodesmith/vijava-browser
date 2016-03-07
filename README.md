# vijava-browser

This application enables browsing a VMware vSphere system, similar to the
Managed Object Browser. It is especially useful for developers working
with the vSphere Java SDK.

## Usage

### Clone the repository

    git clone https://github.com/thecodesmith/vijava-browser
    cd vijava-browser

### Run the application

Use the included gradle wrapper to run the application:

    ./gradlew run

Gradle will bootstrap itself and download the required dependencies.

### Connect to vSphere

To log in to a vSphere server, click `File > Connect`. Example connection
parameters look like this:

    Server: vcenter6.company.com
    Port: 443
    User: <your Active Directory username>
    Password: <your Active Directory password>

Notes:

* The server name does not include "http://" or "/sdk".
* Port 443 is the default vSphere port, but may be different for your server.

Contact your IT admin for details on connecting to your specific server.

## Acknowledgements

The original code for this project was posted on the VMware Developer
forums by [pitchcat](https://communities.vmware.com/people/pitchcat).

Original post "Sample Tool for vijava": https://communities.vmware.com/docs/DOC-11934

## License

This project is licensed under the MIT License.
See [LICENSE.md](LICENSE.md) for details.
