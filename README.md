![Logo](https://www.biocube.ai/assets/img/biocube.svg)


# BioCubeFaceAPI
<div align="justify">
BiocubeFaceAPISDK offers Face Detection APIs for Mobile applications and extensible resource decoding pipelines and automatic resource pooling. Biocube FaceAPISDK is a fast and efficient image processing and provides a unified embedding for face recognition, verification, and authentication. It maps each face image into a euclidean space such that the distances in that space correspond to face similarity, i.e. an image of person A will be placed closer to all the other images of person A as compared to images of any other person present in the dataset. Face Detection is one of the used and popular frameworks of Machine Learning in many different user applications such as Camera apps, Verification Apps, surveillance, and security apps. But it is often underrated due to the complexity it brings for many researchers and Machine Learning experts. This technology has engraved its path on mobile devices as well where many researchers just focus on the performance of Face Detection results only on small handheld devices. Face Detection works with Detection and Estimation algorithms to get us the approximate results.
</div>

# Installation

You can download a aar from GitHub's releases page.

Or use Gradle:

```bash
repositories {
 	...
maven { url 'https://jitpack.io' }
}
```

   ```bash
dependencies {

//User for camera access
def cameraxVersion = "1.3.0-alpha01"
implementation "androidx.camera:camera-view:${cameraxVersion}"
implementation "androidx.camera:camera-camera2:${cameraxVersion}"

//Google Ml Ket
implementation 'com.google.mlkit:face-detection:16.1.5'

	//User for BioCube FaceAPI SDK
implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
implementation 'com.github.biocube-ai:face-api:1.2'

}

   ``` 
## Authors

- [@Biocube]https://www.biocube.ai/)



## Documentation

[Documentation](https://docs.google.com/document/d/1-L7VNy39Iy0c40ASbJphIkWyPqW_QdiBFgI5HwcLN3o/edit?usp=sharing)


## Support

For support, email connect@biocube.ai or join our Slack channel.


## Private Policy
<div align="justify">
This document and the information it contains are provided on a confidential basis with the sole purpose of facilitating business discussions between BioCube Technologies Inc. and the receiving party regarding the implementation of BioCube Solutions. It may not be shared with any other parties or used for any other reason.
</div>


