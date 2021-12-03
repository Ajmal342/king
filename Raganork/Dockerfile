FROM Ajmal342/king:test

RUN git clone https://github.com/Ajmal342/king/ /skl/king
WORKDIR /skl/king 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "king.js"]
