<h2 align="center">CAD-MOTOTAXISTA - Documentação Técnica</h2>

<br>

### Apêndice C – Listagens e Versões das Tecnologias

<p align="justify">
O Apêndice C organiza algumas das principais listagens e versões das tecnologias empregadas no sistema <strong>CAD-MOTOTAXISTA</strong>, reunindo artefatos fundamentais para a compreensão da arquitetura e da infraestrutura da aplicação. No quadro a seguir, o leitor encontrará desde o conjunto de <strong>tecnologias utilizadas (C.1)</strong> até os procedimentos de<strong>execução e acesso ao ambiente produtivo (C.3 e C.3.1)</strong>. Também são apresentados trechos estruturais referentes ao <strong>Controller</strong> e ao <strong>Service</strong> do módulo de Alvará <strong>(C.4 e C.5)</strong>, componentes de segurança e <strong>autenticação (C.6)</strong>, repositórios responsáveis pelo acesso e <strong>persistência de dados (C.7)</strong>, regras de negócio classificadas como <strong>sensíveis (C.8)</strong> e a integração externa com o <strong>serviço ViaCEP (C.8.1)</strong>. Esses elementos fornecem rastreabilidade técnica, padronização dos artefatos e suporte à manutenção evolutiva da aplicação.
</p>

---

<table border="2" align="center" style="border-collapse: collapse; text-align:center;">
  <thead>
    <tr style="background-color:#2F4F4F; color:white;">
      <th colspan="3">APÊNDICE C – LISTAGENS E VERSÕES DAS TECNOLOGIAS</th>
    </tr>
    <tr style="background-color:#708090; color:white;">
      <th>Tema/Listagem</th>
      <th>Disponível em</th>
      <th>Finalidade</th>
    </tr>
  </thead>
  <tbody>
    <!-- Backend -->
    <tr style="background-color:#2F4F4F; color:white;">
      <th colspan="3">Backend / Servidor</th>
    </tr>
    <tr align="center">
      <td>C.1 – Tecnologias</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/tecnologias/C1_versoes-utilizadas.md">Versões</a></td>
      <td>Tecnologias utilizadas</td>
    </tr>
    <tr align="center">
      <td>C.3 – Execução do Sistema</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/config/C3_Execucao_Sistema.md">Executar CAD-MOTOTAXISTA</a></td>
      <td>Inicialização do sistema</td>
    </tr>
    <tr align="center">
      <td>C.3.1 – Aplicação (Produção)</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/aplicacao/C3_1_Acesso_Aplicacao.md">Acesso à Aplicação</a></td>
      <td>Ambiente produtivo</td>
    </tr>
    <tr align="center">
      <td>C.4 – Controller do Módulo de Alvará</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/controller/C4_Controller_Alvara.md">JasperController</a></td>
      <td>Camada de entrada</td>
    </tr>
    <tr align="center">
      <td>C.5 – Service do Módulo de Alvará</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/service/C5_Service_Alvara.md">JasperService</a></td>
      <td>Lógica de negócio</td>
    </tr>
    <tr align="center">
      <td>C.6 – Trechos de Segurança e Autenticação</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/security/C6_Seguranca_Autenticacao.md">Spring Security</a></td>
      <td>Controle de acesso</td>
    </tr>
    <tr align="center">
      <td>C.7 – Repositórios (Repositories)</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/repository/C7_Repositories.md">Spring Data JPA</a></td>
      <td>Acesso a dados</td>
    </tr>
    <tr align="center">
      <td>C.8 – Regras de Negócio Sensíveis</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/service/metodos/C8_Regras_Negocio_Sensiveis.md">Sensíveis</a></td>
      <td>Validações críticas</td>
    </tr>
    <tr align="center">
      <td>C.8.1 – Integração com o Serviço Externo ViaCEP</td>
      <td><a href="https://github.com/Albertinesilva/cad-mototaxista-technical-documentation/blob/main/apendice-c/api/C8_1_Integracao_ViaCEP.md">Integração ViaCep</a></td>
      <td>Consulta de CEP</td>
    </tr>
  </tbody>
</table>

---

## 👨‍💻 Autor

**Albert Silva de Jesus**  
Desenvolvedor Backend Java | Spring Boot

---

### 📎 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/albert-backend-java-spring-boot/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:albertinesilva.17@gmail.com?subject=Contato%20sobre%20o%20projeto%20CAD-MOTOTAXISTA)

---

### 🎓 Contexto Acadêmico

Projeto desenvolvido como Trabalho de Conclusão de Curso (TCC)  
Instituto Federal da Bahia (IFBA).

---

<p align="center">
  <a href="../README.md">🏠 Início</a> |
  <a href="../apendice-d/APENDICE_D.md">Próximo Apêndice ➡</a>
</p>
