export GH_USERNAME='AdamIbz'
export GH_TOKEN=''
GH_IMAGE_NAME='hello-world'
export GH_VER='1.0.0'

echo $GH_TOKEN | docker login ghrcr.io -u $GH_USERNAME --password-stdin
