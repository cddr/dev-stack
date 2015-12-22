FROM ruby

RUN mkdir /in
RUN mkdir /out

VOLUME /in
VOLUME /out

RUN gem install compass listen

CMD ["/usr/local/bundle/bin/sass", "--watch", "/in:/out"]
