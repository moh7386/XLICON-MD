FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/moh7386/XLICON-MD /root/XLICON-MD
WORKDIR /root/XLICON-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
