<Type Name="CertificateEmail" FullName="Microsoft.Azure.Management.WebSites.Models.CertificateEmail">
  <TypeSignature Language="C#" Value="public class CertificateEmail : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateEmail extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CertificateEmail" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateEmail&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type CertificateEmail = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e8783-101">SSL-Zertifikat-e-Mail.</span><span class="sxs-lookup"><span data-stu-id="e8783-101">SSL certificate email.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateEmail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8783-102">Initialisiert eine neue Instanz der CertificateEmail-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e8783-102">Initializes a new instance of the CertificateEmail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateEmail (string id = null, string name = null, string kind = null, string type = null, string emailId = null, Nullable&lt;DateTime&gt; timeStamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string emailId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeStamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional emailId As String = null, Optional timeStamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CertificateEmail : string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CertificateEmail" Usage="new Microsoft.Azure.Management.WebSites.Models.CertificateEmail (id, name, kind, type, emailId, timeStamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="emailId" Type="System.String" />
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e8783-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="e8783-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="e8783-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="e8783-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="e8783-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="e8783-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="e8783-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="e8783-106">Resource type.</span></span></param>
        <param name="emailId"><span data-ttu-id="e8783-107">E-Mail-ID.</span><span class="sxs-lookup"><span data-stu-id="e8783-107">Email id.</span></span></param>
        <param name="timeStamp"><span data-ttu-id="e8783-108">Zeitstempel.</span><span class="sxs-lookup"><span data-stu-id="e8783-108">Time stamp.</span></span></param>
        <summary>
            <span data-ttu-id="e8783-109">Initialisiert eine neue Instanz der CertificateEmail-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e8783-109">Initializes a new instance of the CertificateEmail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailId">
      <MemberSignature Language="C#" Value="public string EmailId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.EmailId" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailId As String" />
      <MemberSignature Language="F#" Value="member this.EmailId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateEmail.EmailId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8783-110">Ruft ab, oder legt die e-Mail-Id fest.</span><span class="sxs-lookup"><span data-stu-id="e8783-110">Gets or sets email id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificateEmail.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificateEmail.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8783-111">Ruft ab, oder legt ihn fest Zeitstempel.</span><span class="sxs-lookup"><span data-stu-id="e8783-111">Gets or sets time stamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>