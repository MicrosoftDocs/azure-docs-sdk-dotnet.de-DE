<Type Name="SalesforceLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService">
  <TypeSignature Language="C#" Value="public class SalesforceLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SalesforceLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SalesforceLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type SalesforceLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Salesforce")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="be87a-101">Verknüpften Dienst für den Salesforce-Connector.</span><span class="sxs-lookup"><span data-stu-id="be87a-101">Linked Service for Salesforce connector.</span></span>
            <span data-ttu-id="be87a-102">Salesforce ist ein System von Cloud-basierten Customer Relationship Management (CRM).</span><span class="sxs-lookup"><span data-stu-id="be87a-102">Salesforce is a cloud-based customer relationship management (CRM) system.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="be87a-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be87a-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceLinkedService (string username, string password, string securityToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string username, string password, string securityToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (username As String, password As String, securityToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService (username, password, securityToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="securityToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="username">To be added.</param>
        <param name="password">To be added.</param>
        <param name="securityToken">To be added.</param>
        <summary>
            <span data-ttu-id="be87a-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="be87a-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentUrl">
      <MemberSignature Language="C#" Value="public string EnvironmentUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnvironmentUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.EnvironmentUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentUrl As String" />
      <MemberSignature Language="F#" Value="member this.EnvironmentUrl : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.EnvironmentUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be87a-105">Optional.</span><span class="sxs-lookup"><span data-stu-id="be87a-105">Optional.</span></span> <span data-ttu-id="be87a-106">Die URL des Salesforce-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="be87a-106">The Salesforce environment URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be87a-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="be87a-107">Required.</span></span> <span data-ttu-id="be87a-108">Das Kennwort der Salesforce-Quelle.</span><span class="sxs-lookup"><span data-stu-id="be87a-108">The password of the Salesforce source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityToken">
      <MemberSignature Language="C#" Value="public string SecurityToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecurityToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.SecurityToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityToken As String" />
      <MemberSignature Language="F#" Value="member this.SecurityToken : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.SecurityToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be87a-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="be87a-109">Required.</span></span> <span data-ttu-id="be87a-110">Das Sicherheitstoken ist erforderlich, um Remotezugriff auf die Salesforce-Quelle.</span><span class="sxs-lookup"><span data-stu-id="be87a-110">The security token is required to remotely access the Salesforce source.</span></span>
            <span data-ttu-id="be87a-111">Referenz: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_concepts_security.htm</span><span class="sxs-lookup"><span data-stu-id="be87a-111">Reference: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_concepts_security.htm</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SalesforceLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be87a-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="be87a-112">Required.</span></span> <span data-ttu-id="be87a-113">Der Benutzername der Salesforce-Quelle.</span><span class="sxs-lookup"><span data-stu-id="be87a-113">The username of the Salesforce source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>