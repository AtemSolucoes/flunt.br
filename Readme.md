# About

Flunt.Br is a lib with a set of extensions for [Flunt](https://github.com/andrebaltieri/flunt]) to validate Brazilian attributes, like cpf, cnpj and phone

# Sobre
Flunt.Br é uma biblioteca com um conjunto de extensões para o [Flunt](https://github.com/andrebaltieri/flunt]) para validar atributos Brasileiros, como cpf, cnpj e telefone.

# Usage

This lib enables in your validation contracts this methods:

  ```
  var contratct = new Contract()
      .IsCpf(person.document, "Document", "Invalid document")
      .IsCnpj(company.document, "Document", "Invalid document")
      .IsPhone(company.phone, "Phone", "Invalid phone")
      .IsCellPhone(person.cellphone, "Phone", "Invalid cellphone")
  ```
  
# Como Usar

Essa biblioteca possibilita esses métodos em seus Validation Contracts:

  ```
  var contratct = new Contract()
      .IsCpf(pessoa.documento, "Documento", "Documento inválido")
      .IsCnpj(empresa.documento, "Documento", "Documento inválido")
      .IsPhone(empresa.telefone, "Telefone", "Telefone inválido")
      .IsCellPhone(pessoa.telefone, "Telefone", "Telefone inválido")
  ```
