# PassWall 2 Setup Guide for GL.iNet MT3000

This guide will walk you through the steps to set up PassWall 2 on your GL.iNet MT3000 router.

## Prerequisites
Before you begin, make sure you have the following:

- GL.iNet MT3000 router
- Internet connection
- Computer or mobile device

## Setup 
To set up PassWall 2 on your GL.iNet MT3000 router using the `passwall2x.sh` file, follow these steps:

1. Clone the PassWall 2 repository by running the following command in your terminal:
    ```
    git clone https://github.com/mgkyawzayya/passwall-mt3000.git passwall
    ```

2. Move the cloned repository to your OpenWrt device using `scp` command. Replace `your-username` and `your-device-ip` with your actual username and device IP address:
    ```
    scp -r passwall/ your-username@your-device-ip:/path/to/destination
    ```

3. SSH into your OpenWrt device by running the following command:
    ```
    ssh your-username@your-device-ip
    ```

4. Navigate to the destination folder where you moved the PassWall 2 repository:
    ```
    cd /path/to/destination/PassWall 2
    ```

5. Make the `passwall2x.sh` file executable by running the following command:
    ```
    chmod +x passwall2x.sh
    ```

6. Run the `passwall2x.sh` file to start the PassWall 2 installation process:
    ```
    ./passwall2x.sh
    ```

7. Follow the on-screen instructions to configure PassWall 2 according to your preferences.

Once the installation is complete, PassWall 2 will be set up on your GL.iNet MT3000 router. Enjoy secure and private internet browsing!
