In adaptive_cub there are the following Matlab's codes:

-adaptive_cub_sphpgon: this code implements an adaptive algorithm for numerical integration over spherical polygons. The algorithm works by recursively subdividing the polygon into smaller spherical triangles,
                       where needed, until a desired level of accuracy is reached.
                       
-demo_sphplg: this is a demonstration script that shows in some cases the capabilities of the adaptive_cub_sphpgon algorithm. The user can choose a specific domain (example) and an integrand function (function_type),
              and then it performs the adaptive integration using different tolerance levels. 
              
              The script generates several plots to visualize the results, including:
              
              the initial triangulation of the domain.
              
              The adaptive triangulations for three different tolerance levels. 
              In these images is shown a color map of the integrand function over the domain.
              
              The quadrature nodes of a non-adaptive quadrature method with 40 as degree of exactness.
              
-other supporting codes: these are auxiliary functions and scripts that are necessary for the correct functioning of the main codes.
