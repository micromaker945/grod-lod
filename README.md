# grod-lod
echo Hello, world!
echo Add other actions to build,
echo test, and deploy your projects
# Set up docker to authenticate 
# via gcloud command line tool
gcloud auth configure-docker
# Build a docker container and
# push it to ECR so that it can 
# be deployed to ESC
cargo build --verbose
cargo test --verbose
npm install
npm run build --if-present
npm test
