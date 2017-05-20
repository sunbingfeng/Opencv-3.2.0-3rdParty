OpenCV-3.2.0 install 3rd-party
================================

#### ippicv

查看ippicv的downloader.cmake文件中写明的版本是：ippicv_linux_20151201.tgz

download下来后丢到下面的路径上：

opencv-3.2.0/3rdparty/ippicv/downloads/linux-808b791a6eac9ed78d32a7666804320e

**808b791a6eac9ed78d32a7666804320e**为该文件的md5sum

#### protobuf

opencv_contrib-3.2.0/modules/dnn/.download/bd5e3eed635a8d32e2b99658633815ef/v3.1.0

同上，**bd5e3eed635a8d32e2b99658633815ef**为protobuf文件的md5sum

#### xfeatures

这个更麻烦些，直接把.download文件夹内容全部copy到opencv_contrib\modules\xfeatures2d\cmake\.download

最终的参考tree格式：

C:\p\opencv_contrib\modules\xfeatures2d\cmake\.download>tree /F

├───0ae0675534aa318d9668f2a179c2a052

│       boostdesc_lbgm.i

│

├───0ea90e7a8f3f7876d450e4149c97c74f

│       boostdesc_bgm.i

│

├───151805e03568c9f490a5e3a872777b75

│       vgg_generated_120.i

│

├───202e1b3e9fec871b04da31f7f016679f

│       boostdesc_binboost_064.i

│

├───232c966b13651bd0e46a1497b0852191

│       boostdesc_bgm_bi.i

│

├───324426a24fa56ad9c5b8e3e0b3e5303e

│       boostdesc_bgm_hd.i

│

├───7126a5d9a8884ebca5aea5d63d677225

│       vgg_generated_64.i

│

├───7cd47228edec52b6d82f46511af325c5

│       vgg_generated_80.i

│

├───98ea99d399965c03d555cef3ea502a0b

│       boostdesc_binboost_128.i

│

├───e6dcfa9f647779eb1ce446a8d759b6ea

│       boostdesc_binboost_256.i

│

└───e8d0dcd54d1bcfdc29203d011a797179

|        vgg_generated_48.i