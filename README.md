# HelloOpenCV
OpenCV VERSION : 4.1.1
opencv android api



# project clone
git clone https://github.com/hello-bryan/HelloOpenCV.git



# MainActivity
<img src='https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FIUXK4%2FbtqygUsuxOd%2FasMp0oVhkWPPKy3AKXQ8M0%2Fimg.jpg' width='200' />


                    Mat gray = new Mat();
                    Utils.bitmapToMat(bitmap, gray);

                    Imgproc.cvtColor(gray, gray, Imgproc.COLOR_RGBA2GRAY);

                    Bitmap grayBitmap = Bitmap.createBitmap(gray.cols(), gray.rows(), null);
                    Utils.matToBitmap(gray, grayBitmap);
