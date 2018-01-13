<Type Name="TableStorageModel" FullName="Microsoft.WindowsAzure.Storage.Table.TableStorageModel">
  <TypeSignature Language="C#" Value="public class TableStorageModel : Microsoft.Data.Edm.Library.EdmModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableStorageModel extends Microsoft.Data.Edm.Library.EdmModel implements class Microsoft.Data.Edm.IEdmElement, class Microsoft.Data.Edm.IEdmModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableStorageModel" />
  <TypeSignature Language="VB.NET" Value="Public Class TableStorageModel&#xA;Inherits EdmModel" />
  <TypeSignature Language="F#" Value="type TableStorageModel = class&#xA;    inherit EdmModel&#xA;    interface IEdmModel&#xA;    interface IEdmElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Data.Edm.Library.EdmModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt ein Datenmodell, die von OData für die Tabelle Transaktionen verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableStorageModel (string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableStorageModel.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableStorageModel : string -&gt; Microsoft.WindowsAzure.Storage.Table.TableStorageModel" Usage="new Microsoft.WindowsAzure.Storage.Table.TableStorageModel accountName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableStorageModel" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Data.Edm.IEdmModel.FindDeclaredType">
      <MemberSignature Language="C#" Value="Microsoft.Data.Edm.IEdmSchemaType IEdmModel.FindDeclaredType (string qualifiedName);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Data.Edm.IEdmSchemaType Microsoft.Data.Edm.IEdmModel.FindDeclaredType(string qualifiedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableStorageModel.Microsoft#Data#Edm#IEdmModel#FindDeclaredType(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function FindDeclaredType (qualifiedName As String) As IEdmSchemaType Implements IEdmModel.FindDeclaredType" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Data.Edm.IEdmModel.FindDeclaredType(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Data.Edm.IEdmSchemaType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="qualifiedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="qualifiedName">Der qualifizierte Name des gefunden Typs.</param>
        <summary>
            Für einen Typ mit dem angegebenen Namen in diesem Modell sucht, und erstellt einen neuen Typ aus, wenn kein solcher Typ vorhanden.
            </summary>
        <returns>Der angeforderte Typ oder den neuen Typ erstellt, wenn kein solcher Typ vorhanden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>