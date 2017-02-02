def PULL_REQUEST = env.CHANGE_ID
def workspace = pwd()
node('master'){

stage('test'){
  echo "${PULL_REQUEST}"
  echo "${workspace}"
}

}
