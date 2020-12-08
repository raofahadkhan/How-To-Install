    ## How To Install GitHub Desktop on Ubuntu:

        **It is a two step process:**

        ### 1.To set up the package repository, run these commands:

        ```

        wget -qO - https://packagecloud.io/shiftkey/desktop/gpgkey | sudo apt-key add -


        sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/shiftkey/desktop/any/ any main" > /etc/apt/sources.list.d/packagecloud-shiftky-desktop.list'


        sudo apt-get update

        ```

        ### 2.Then install GitHub Desktop:


        `sudo apt install github-desktop`

### That's it and if you find that repo useful give it a STAR.
