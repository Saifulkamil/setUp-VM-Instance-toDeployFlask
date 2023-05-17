# setUp-VM-Instance-toDeployFlask
    sudo apt update
    sudo apt upgrade -y (optionals)

    python3 --version


add repo(optionals)
###  python3.10-full belom di coba

    sudo echo "deb http://ftp.de.debian.org/debian sid main" >> /etc/apt/sources.list 

### Python 3.9.2

    sudo echo "deb http://ftp.de.debian.org/debian bullseye main " >> /etc/apt/sources.list 

# atau
    sudo nano /etc/apt/sources.list

    deb http://ftp.de.debian.org/debian bullseye main 
    deb http://ftp.de.debian.org/debian sid main 
    deb http://ftp.de.debian.org/debian sid main 



    sudo apt install python3-pip -y

    sudo apt-get install python3-venv  atau // pip3 install virtualenv


git --version
    sudo apt-get install git -y (optionals)

    git clone https://github.com/sepol-sys/project_flask_CI_CD.git //ganti repo nya

        sudo python3 -m venv myenv # optional jika sudah ada virtual envirotmen ngak usah lagi buat


        . myenv/Scripts/activate       //pastikan sudah masuk ke myenv //ganti myenv dengan nama env-nya

        pip3 install -r requirements.txt // ada beberapa yang harus di rubah

        python3 run.py

        deactivate        // untuk keluar myenv  







dpkg --print-architecture



