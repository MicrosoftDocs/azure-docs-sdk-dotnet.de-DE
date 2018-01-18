<Type Name="BatchTokenCredentials" FullName="Microsoft.Azure.Batch.Auth.BatchTokenCredentials">
  <TypeSignature Language="C#" Value="public class BatchTokenCredentials : Microsoft.Azure.Batch.Auth.BatchCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchTokenCredentials extends Microsoft.Azure.Batch.Auth.BatchCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchTokenCredentials&#xA;Inherits BatchCredentials" />
  <TypeSignature Language="F#" Value="type BatchTokenCredentials = class&#xA;    inherit BatchCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Auth.BatchCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0218a-101">Azure Active Directory token-Anmeldeinformationen für ein Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="0218a-101">Azure Active Directory token credentials for an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchTokenCredentials (string baseUrl, Func&lt;System.Threading.Tasks.Task&lt;string&gt;&gt; tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baseUrl, class System.Func`1&lt;class System.Threading.Tasks.Task`1&lt;string&gt;&gt; tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Auth.BatchTokenCredentials.#ctor(System.String,System.Func{System.Threading.Tasks.Task{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUrl As String, tokenProvider As Func(Of Task(Of String)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Auth.BatchTokenCredentials : string * Func&lt;System.Threading.Tasks.Task&lt;string&gt;&gt; -&gt; Microsoft.Azure.Batch.Auth.BatchTokenCredentials" Usage="new Microsoft.Azure.Batch.Auth.BatchTokenCredentials (baseUrl, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUrl" Type="System.String" />
        <Parameter Name="tokenProvider" Type="System.Func&lt;System.Threading.Tasks.Task&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="baseUrl"><span data-ttu-id="0218a-102">Der Batch-Dienst-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="0218a-102">The Batch service endpoint.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0218a-103">Eine Funktion, die ein Authentifizierungstoken zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="0218a-103">A function which returns an authentication token.</span></span></param>
        <summary>
            <span data-ttu-id="0218a-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Auth.BatchTokenCredentials" /> Klasse mit der angegebenen Batch-Dienst-Endpunkt und Authentifizierung Tokenanbieter Funktion.</span><span class="sxs-lookup"><span data-stu-id="0218a-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Auth.BatchTokenCredentials" /> class with the specified Batch service endpoint and authentication token provider function.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchTokenCredentials (string baseUrl, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baseUrl, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Auth.BatchTokenCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUrl As String, token As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Auth.BatchTokenCredentials : string * string -&gt; Microsoft.Azure.Batch.Auth.BatchTokenCredentials" Usage="new Microsoft.Azure.Batch.Auth.BatchTokenCredentials (baseUrl, token)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUrl" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baseUrl"><span data-ttu-id="0218a-105">Der Batch-Dienst-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="0218a-105">The Batch service endpoint.</span></span></param>
        <param name="token"><span data-ttu-id="0218a-106">Ein Authentifizierungstoken, die von Azure Active Directory bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="0218a-106">An authentication token provided by Azure Active Directory.</span></span></param>
        <summary>
            <span data-ttu-id="0218a-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Auth.BatchTokenCredentials" /> -Klasse mit den angegebenen Batch-Dienst-Endpunkt und die Authentifizierung token.</span><span class="sxs-lookup"><span data-stu-id="0218a-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Auth.BatchTokenCredentials" /> class with the specified Batch service endpoint and authentication token.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.Tasks.Task&lt;string&gt;&gt; TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`1&lt;class System.Threading.Tasks.Task`1&lt;string&gt;&gt; TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Auth.BatchTokenCredentials.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As Func(Of Task(Of String))" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Func&lt;System.Threading.Tasks.Task&lt;string&gt;&gt;" Usage="Microsoft.Azure.Batch.Auth.BatchTokenCredentials.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.Tasks.Task&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0218a-108">Ruft eine Funktion, die ein Authentifizierungstoken zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="0218a-108">Gets a function which returns an authentication token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>