<Type Name="StoredProcedure" FullName="Microsoft.Azure.Documents.StoredProcedure">
  <TypeSignature Language="C#" Value="public class StoredProcedure : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StoredProcedure extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.StoredProcedure" />
  <TypeSignature Language="VB.NET" Value="Public Class StoredProcedure&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StoredProcedure = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c44e9-101">Stellt eine gespeicherte Prozedur in der Azure-Cosmos-DB-Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="c44e9-101">Represents a stored procedure in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks> 
            <span data-ttu-id="c44e9-102">Azure Cosmos-Datenbank können vollständig in direkt innerhalb des Datenbankmoduls unter der Datenbanktransaktion auszuführenden JavaScript geschriebene Anwendungslogik.</span><span class="sxs-lookup"><span data-stu-id="c44e9-102">Azure Cosmos DB allows application logic written entirely in JavaScript to be executed directly inside the database engine under the database transaction.</span></span>
            <span data-ttu-id="c44e9-103">Weitere Informationen finden Sie in der serverseitige JavaScript-API-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="c44e9-103">For additional details, refer to the server-side JavaScript API documentation.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoredProcedure ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.StoredProcedure.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c44e9-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c44e9-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.StoredProcedure.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Documents.StoredProcedure.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c44e9-105">Ruft ab oder legt den Text der Azure-Cosmos-Datenbank gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="c44e9-105">Gets or sets the body of the Azure Cosmos DB stored procedure.</span></span>
            </summary>
        <value><span data-ttu-id="c44e9-106">der Text der gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="c44e9-106">The body of the stored procedure.</span></span></value>
        <remarks><span data-ttu-id="c44e9-107">Muss eine gültige JavaScript-Funktion.</span><span class="sxs-lookup"><span data-stu-id="c44e9-107">Must be a valid JavaScript function.</span></span> <span data-ttu-id="c44e9-108">Für z. B. "-Funktion () {GetContext () .getResponse () .setBody ("Hello World!");}"</span><span class="sxs-lookup"><span data-stu-id="c44e9-108">For e.g. "function () { getContext().getResponse().setBody('Hello World!'); }"</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>