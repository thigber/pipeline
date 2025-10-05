pipeline { //aqui você diz ao Jenkins o que fazer, em que ordem e onde.
    agent any //Indica onde as etapas da pipeline vão rodar "any" roda em qualquer ambiente disponível
    stages { //Cada stage representa uma fase do processo de entrega (build, test, deploy...).
        stage('Build') {//aqui seria o momento de compilar o código
            steps {
                echo 'Compilando...'
                        }
        }
        stage('Test') { //Representa a fase de testes automatizados. O Jenkins executaria scripts de teste e mostraria no console se algo falhou.
            steps {
                echo 'Rodando testes...'
            }
        }
        stage('Deploy') { //Essa etapa seria responsável por enviar o sistema para produção, publicar no servidor
            steps {
                echo 'Deploy realizado com sucesso!!!!' //o echo só imprime uma mensagem simulando que o deploy deu certo:
            }
        
        }
    }
}