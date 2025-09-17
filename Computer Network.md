Computer Network
    Aula 1:

        Aspectos Fisicos e Aspectos logicos:
            Aspectos fisicos: Refere-se aos componentes propriamente ditos, como cabo de redes, computadores, dispositivos, fibra ótica e 
            wireless. Este são os elementos com os quais interagimos diretamentes e que constituem os meios de condução e conectização das redes

            Aspectos logicos: Refere-se aos endereços, a divisão, a indentificação, a segurança, ao controle e a verificação e validação das 
            informações transmitidas. Este aspecto trata das regras e protocolos que garantem a comunicação eficaz e segura entres os 
            dispositivos na rede 

        ISO - International Organization for Standardization:
            Padronização e certificação de qualidade
            Modelo reproduzivel por qualquer fabricante 

        ARPANET: Foi a primeira rede de computadores, criada em 1969 pela Agencia de Projetos e Pesquisa Avançadas dos EUA (ARPA), que ligava 
        a Universidade da Califórnia, Los Angeles (UCLA), o Instituto de Pesquisas de Stanford (SRI),
        a Universidade da Califórnia, Santa Bárbara (UCSB) e a Universidade de Utah

        Locais (LAN) – limitadas a um ambiente físico, como um escritório ou residência.
        Metropolitanas (MAN) – abrangendo uma cidade ou região.
        Globais (WAN) – interligando países e continentes.

        Ou até “flutuando” sobre nossas cabeças, por meio de satélites e foguetes, como no caso dos serviços do Elon Musk.

    Aula 2:
        indetificar e diferenciar infraestutura ativa e passiva

            infraestutura ativa:

                roteador: A função primordial do roteador é conectar redes distintas, por tanto ele vai fazer a conexão entre a provedora
                de intenet e a sua rede servidores, com o passar do tempo o roteador foi pegando a função dos demais, switch, accsess point

                modens: Convertem sinais digitais em analogicos e vice-versa

                accsess point:Tem a mesma função do roteador porem ele não tem cabos, apenas 1 pra conectar a rede e a transforma em sem fio 

                Switch: 
                    Responsavelpor fazer uma conexão entre as maquinas da empresa
                        Funcionamento interno de um switch:
                                            Recebimento de frame
                                            Aprendizado de endereço MAC
                                            Consulta na tabela MAC
                                            Encaminhamento inteligente

                                        Tabela MAC:
                                                Mapear endereços MAC e associa-los às portas do switch 
                    switch gigabity e

                    Tipos de switch  

                        switch POE: que conectam em cameras por exemplo, ele energiza e liga na rede 

                        Switch gerenciavel: ele pode ser configurado por algum dispositovo, como computador, notebooks e celulares. 
                        ja que ele é gerenciavel é possivel fazer uma separação, como exemplo fazer um grupo pro A e pro B para diferentes 
                        setores no mesmo switch, configuraveis com recursos avançados , VLANS, QOS(qualidadade de serviço), SNM(Monitoramento)


                        Switch não gerenciavel: disposi, 

            infraestutura passiva: é comosta por elementos não energizados que dão suporte fisicos, organizam e conectam os dispositivos ativos 
            da rede. São fundamentais para manter a rede organizada, seguras e eficentes 

                    keysstones,
                    cabos de rede UTP/STP
                    conectores RJ45
                    tomada RJ45 femea 
                    patch paineis ( carregados e descarregados ): Responsavel por organizar e centralizar as conexões de rede em um rack
                    organizadores de cabos
                    Racks       


    Aula 3:
        Modelo TCP/IP
        
            4° Aplicação
            3° Transporte
            2° internet
            1° Rede 

        Modelos OSI(Open Systems Interconnection)
            Importacia do modelo OSI para os desenvolvedores

            É separado em 7 etapas camadas

            7° Aplicação (Whatsapp, chromme, email)
            6° Aprensentação (Criptografia)
            5° Sessão (entrar, verificar e finalizar a sessão)
            4° Transporte (Relacionada a escolher o melhor serviço para fazer a entrega como TCP e UDP)
                TCP: garante a entrga ordenada e sem erroe
                UDP: é mais rapido, mas não oferece garantia (como video no YouTube, comunicação em geral)
            3° Rede (Protocolo de IP)
            2° Dados (Enlance)(MAC)
            1° Fisica (Modelos de transmissão, como wifi e cabos/fibra optica)

        Internet, Extranet, Entranete e Ethernet

            internet:  é uma rede global que conecta bilhões de dispositivos em todo o mundo, utilizando o conjunto de protocolos TCP/IP para troca de dados. Ela é pública, descentralizada e acessível, oferecendo serviços como navegação web, e-mails, redes sociais e streaming.

                Rede Global: é uma rede global interligada por cabos de fibra opticas 
                protocolos:São um conjuto de regras que definem como os dados são formados como TCP/IP E HTTP E HTTPS

                Serviços: O que são: A internet oferece uma vasta gama de serviços que possibilitam a troca de informações e a interação entre usuários como WWW e FTP

                Acessibilidade:Acessibilidade na internet é o desenvolvimento de plataformas e serviços digitais que são projetados para que pessoas com deficiência e outras limitações possam perceber, entender, navegar, interagir e contribuir de forma efetiva.

            Intranet: Limitada a região geografica da empresa
                Rede Privada: Acesso restritos a usuarios autorizados da organização
                Funcionalidades: Compartilhamento de informações e recursos internos
                Segurança: Ambiente controlado para comunicação e colaboração corporativas

            Extranet:

                Extensão da intranet: Permite comunicação segura com usuarios externos
                Acesso controlado: Conecta parceiros e fornecedores a sistemas especificos 
                Segurança intermediaria:
            Ethernet: tem haver com cabeamento que interliga cada componente dentro do sevidor, como impressoras, switches e computadores 

        Aula 4: Cabos de Rede: Estrutura, Transmissão e Conectividade

            Por fim, todo cabeamento depende de padrões e conectividade passiva. Os padrões T568A e T568B:       
                    T568A e T568B são dois padrões de pinagem (a ordem das cores dos fios) para conectores RJ45 em cabos de rede, sendo a principal diferença a troca das posições do par verde e do par laranja. O T568B é o mais comum em instalações comerciais e residenciais modernas, enquanto o T568A é um padrão mais antigo

            A transmissão de dados acontece por meio dos pares de fios responsáveis pelo Tx (Transmitir) e pelo Rx (Receber)

                TX(Transmitir)

                RX(Receber)

                simplex: informação segue apenas em um sentido

                Half-duplex: a comunicação é bidimencinal mas tambem alterna

                full-duplex transmissão ocorre nos dois sentidos ao mesmo tempo, como acontece nas redes Ethernet modernas
            
            O cabeamento horizontal: conecta diretamente as estações de trabalho, telefones IP, impressoras e access points às salas de telecomunicações do mesmo andar

            cabeamento vertical (backbone): é a espinha dorsal da rede, interligando diferentes andares, prédios ou data centers e permitindo o transporte de grandes volumes de dados entre os concentradores de distribuição.

            PoE (Power over Ethernet): ainda permitem que dados e energia trafeguem pelo mesmo cabo, alimentando câmeras, access points e telefones IP de forma prática e segura.
            
            Cat3 e Cat5 já estão obsoletos, mas o Cat5e ainda é bastante usado para Gigabit Ethernet
            Cat3: suporta velocidades de até 10 Mbps
            Cat5: 100 MHz e 100 Mbps
            O Cat6 e o Cat6a são recomendados em instalações modernas, suportando até 10 Gbps
            Cat6: suportam velocidades de até 1000 Mbps, ou um Gigabit por segundo
            Cat6a: 500 MHz velocidade Até 10 Gbps em até 100 metros 
            Cat8: é voltado para data centers de alta performance, atingindo até 40 Gbps em curtas distâncias.