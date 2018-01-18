<Type Name="TransparentDataEncryptionActivity" FullName="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryptionActivity : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryptionActivity extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryptionActivity&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionActivity = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fa4aa-101">Stellt einen transparenten datenbankverschlüsselung Scan dar.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-101">Represents a database transparent data encryption Scan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fa4aa-102">Initialisiert eine neue Instanz der TransparentDataEncryptionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-102">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity (string id = null, string name = null, string type = null, string location = null, string status = null, Nullable&lt;double&gt; percentComplete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, string status, valuetype System.Nullable`1&lt;float64&gt; percentComplete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional status As String = null, Optional percentComplete As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity : string * string * string * string * string * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity" Usage="new Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity (id, name, type, location, status, percentComplete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fa4aa-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="fa4aa-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="fa4aa-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="fa4aa-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="fa4aa-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-106">Resource location.</span></span></param>
        <param name="status"><span data-ttu-id="fa4aa-107">Der Status der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-107">The status of the database.</span></span> <span data-ttu-id="fa4aa-108">Folgende Werte sind möglich: "Verschlüsseln", 'Entschlüsseln'</span><span class="sxs-lookup"><span data-stu-id="fa4aa-108">Possible values include: 'Encrypting', 'Decrypting'</span></span></param>
        <param name="percentComplete"><span data-ttu-id="fa4aa-109">Der prozentuale Anteil der transparent Data Encryption Überprüfung für eine Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-109">The percent complete of the transparent data encryption scan for a database.</span></span></param>
        <summary>
            <span data-ttu-id="fa4aa-110">Initialisiert eine neue Instanz der TransparentDataEncryptionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-110">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa4aa-111">Ruft die Position der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-111">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa4aa-112">Ruft den abgeschlossenen Prozentsatz der transparent Data Encryption Überprüfung für eine Datenbank.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-112">Gets the percent complete of the transparent data encryption scan for a database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa4aa-113">Ruft den Status der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="fa4aa-113">Gets the status of the database.</span></span> <span data-ttu-id="fa4aa-114">Folgende Werte sind möglich: "Verschlüsseln", 'Entschlüsseln'</span><span class="sxs-lookup"><span data-stu-id="fa4aa-114">Possible values include: 'Encrypting', 'Decrypting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>