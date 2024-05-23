pipeline {
agent any
stages{ stages('helloo'){
steps{ echo 'hello word'
}
}
stage ('build'){
steps{
echo 'dev' 
}
}
