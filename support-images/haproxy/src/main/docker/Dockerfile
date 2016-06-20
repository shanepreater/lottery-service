FROM haproxy:1.6.5

RUN mkdir -p /config/haproxy

# Copy the default version in to use for the moment until the actual config is pulled in from the volume.
COPY haproxy.cfg /config/haproxy/haproxy.cfg

#Sym link to the new config location instead.
RUN ln -s /config/haproxy/haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

VOLUME /config/haproxy
