# Document_Scanner
The process was accomplished using OpenCV and can be broken down into just four simple steps:

<ol>
  <li>Detect edges.</li>
  <li>Use the edges to find the contour (outline) representing the paper to be scanned.</li>
<li>Apply a perspective transform to obtain the top-down view of the document, a 90-degree view of the image.</li>
  <li>Apply thresholding to get a nice, clean black and white feel to the piece of paper.</li>
</ol>
