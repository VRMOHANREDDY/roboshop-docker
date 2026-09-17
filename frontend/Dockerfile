FROM nginx:1.24.0                    #taken nginx
RUN rm -rf /usr/share/nginx/html/*   # removed default code
RUN rm -rf /etc/nginx/nginx.conf     # placed the code here
RUN rm -rf /etc/nginx/conf.d/default.conf  # remove default.conf in conf.d remove
COPY static/ /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/nginx.conf