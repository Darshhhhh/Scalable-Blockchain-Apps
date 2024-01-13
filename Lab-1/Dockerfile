FROM node:18-alpine
WORKDIR /Lab-1/
COPY public/ /Lab-1/
COPY src/ /Lab-1/src
COPY package.json /Lab-1/    
RUN npm install
CMD ["npm", "run dev"]