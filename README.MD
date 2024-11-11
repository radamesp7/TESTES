```mermaid
%%{init: {'theme': 'default'}}%%
%% Usa a sintaxe do diagrama de casos de uso UML
    usecase UC1 as "Consultar Atividades"
    usecase UC2 as "Registrar Nova Tarefa"
    usecase UC3 as "Atualizar Tarefa Existente"
    usecase UC4 as "Concluir/Cancelar Tarefa"
    usecase UC5 as "Adicionar Novo Colaborador"
    usecase UC6 as "Gerar Relatórios de Atividades"
    usecase UC7 as "Filtrar Atividades por Categoria"
    
    actor João as "Usuário Comum"
    actor Mariana as "Administrador do Sistema"
    
    João --> UC1
    João --> UC2
    João --> UC3
    João --> UC4

    Mariana --> UC5
    Mariana --> UC6
    Mariana --> UC7
