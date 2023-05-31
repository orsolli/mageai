`docker build -t mage_dyreparken_regnskap .`


`docker run -p 6789:6789 -v $(pwd):/home/mage_code mage_dyreparken_regnskap`