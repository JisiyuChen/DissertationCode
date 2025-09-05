Code File Descriptions:
	sentiment_analysis_optimization11new.ipynb: Contains the complete code for the multimodal model proposed in this study, as well as the code for decompressing the image compressed package.
	moondream.ipynb: Code for fine-tuning the moondream2 model to process multiple images at once.
	OnlyImage.ipynb: Code for classifying image emotions solely based on image content.
	OnlyText.ipynb: Code for classifying image emotions solely based on text content.


Code Execution Steps:
1. Upload and save all code files, the image compressed package, and the labeled document to Colab, ensuring that all the following files are in the same directory level.
	Total folder link: https://drive.google.com/drive/folders/1gP4R2ht8TVAHciTbnosh4hZU_5W-tXaN?usp=sharing
	Links:
		sentiment_analysis_optimization11new.ipynb: https://drive.google.com/file/d/1ddMDKmAaFmN4pwiIaIZGrjGUPZee_KJI/view?usp=sharing
		moondream.ipynb: https://drive.google.com/file/d/1sAc8U5zzghspgFR5zlo_-_ge7haSKVty/view?usp=sharing
        	OnlyImage.ipynb: https://drive.google.com/file/d/1PS16S07AV8yWRx8mNJNtCx5wQTSNdVrL/view?usp=sharing
        	OnlyText.ipynb: https://drive.google.com/file/d/1sqshfieZ8tNxgzzzRFdy3L2jDQA0jUHX/view?usp=sharing
        	Image compressed package link: https://drive.google.com/file/d/12jNBK9fvektvUaIksd7H6Nz6oYPEnwMK/view?usp=sharing
        	Labeled document link: https://drive.google.com/file/d/1Xqc6fYEZ13ejtgPYeNVwGtNyVd-LqHUu/view?usp=sharing
2. Modify the paths of the following parameters in all code files to your Colab paths:
    	ZIP_DIR='/content/drive/MyDrive/Dissertation/images.zip'
    	UNZIP_IMAGE_DIR='/content/drive/MyDrive/Dissertation/images'
    	IMAGE_DIR = "/content/drive/MyDrive/Dissertation/images"
    	CSV_FILE = "/content/drive/MyDrive/Dissertation/labels.csv"
    	OUTPUT_DIR = "/content/drive/MyDrive/Dissertation/"
    	CACHE_DIR = "/content/drive/MyDrive/Dissertation/cache"
3. Run the sentiment_analysis_optimization11new.ipynb file first. This code includes the decompression code to decompress the image compressed package.
4. Subsequently, you can run the code in the moondream.ipynb, OnlyImage.ipynb, and OnlyText.ipynb files separately.