# gitHub-actions

## getting Checkout action from GitHub market place: 
   https://github.com/marketplace/actions/checkout

## using third party libraries
    cowsay is a third party library which is used for generating ASCII Artwork

## installing cowsay library before generating ascii Artwork
    sudo apt-get install cowsay -y

## to run script in the workflow, permissions needs to be granted
    chmod +x abcscript.sh

## to share data between various jobs Artifact is used 

### upload artifact is used to upload the data
    https://github.com/marketplace/actions/upload-a-build-artifact#usage

### download artifact is used to download the data 
    https://github.com/marketplace/actions/download-a-build-artifact#usage

this is for testing only