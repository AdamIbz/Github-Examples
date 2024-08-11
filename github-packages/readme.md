export GH_USERNAME='AdamIbz'
export GH_TOKEN='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'
GH_IMAGE_NAME='hello-world'
export GH_VER='1.0.0'

echo $GH_TOKEN | docker login ghrcr.io -u $GH_USERNAME --password-stdin
