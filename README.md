# php-image-compressor-on-upload
Easily compress image before uploading your images to the server. Also support compressing image on the go without uploading a file
Certain PHP websites utilize upload forms to allow users to submit images. If these sites receive a large number of photos, they might surpass the disk space allotted by the hosting company.

To prevent surpassing the allocated disk space while still accommodating numerous image files uploaded by site users, employing a compression solution can be beneficial.

By employing this package, it becomes possible to decrease the file size of uploaded images. This is achieved by processing the image files and saving them with a reduced quality factor.

While the image quality may be compromised, the files will occupy significantly less space. As a result, PHP developers who adopt this method can avoid incurring additional expenses with the hosting company, especially when managing websites that require a large number of images that could potentially consume substantial disk space.
