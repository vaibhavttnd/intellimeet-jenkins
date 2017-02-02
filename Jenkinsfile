def PULL_REQUEST = env.CHANGE_ID

node('master'){
def workspace = pwd()
stage('test'){
  echo "${PULL_REQUEST}"
  echo "${workspace}"
}

}
