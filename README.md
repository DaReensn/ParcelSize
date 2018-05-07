# ci_cd-pipeline
mehr spaß
docker build -t parcel-api .

docker run -it --rm --network host --name=ParcelSize parcel-api java -jar ./build/libs/ParcelSize.jar