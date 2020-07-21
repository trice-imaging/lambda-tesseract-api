### Used to build Tesseract as a Lambda Layer for the Anonymization Service


*Note* : Docker must be installed 

### Fast setup to create tesseract and python layers

clone the repo

```cd lambda-tesseract-api/```

```bash build_py37_pkgs.sh```

```bash build_tesseract4.sh```

Done ! You should see some .zip files created in your directory.

#### Check the Medium [link](https://medium.com/@amtam0/tesseract-4-serverless-api-using-aws-lambda-and-python-in-minutes-91279e73a50) to setup lambda and Api in AWS console

# References

[Ocr Layer] (https://github.com/bweigel/aws-lambda-tesseract-layer)

[Python libraries to layers] (https://github.com/tiivik/LambdaZipper)

[python3.7 lambda] (https://github.com/lambci/docker-lambda)
