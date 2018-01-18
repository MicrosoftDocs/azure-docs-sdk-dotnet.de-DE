<Type Name="TransparentDataEncryptionActivity" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity">
  <TypeSignature Language="C#" Value="public class TransparentDataEncryptionActivity : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransparentDataEncryptionActivity extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class TransparentDataEncryptionActivity&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionActivity = class&#xA;    inherit SqlSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bd428-101">Stellt eine Azure SQL Datenbank Transparent Data Encryption Überprüfung dar.</span><span class="sxs-lookup"><span data-stu-id="bd428-101">Represents an Azure SQL Database Transparent Data Encryption Scan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd428-102">Initialisiert eine neue Instanz der TransparentDataEncryptionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bd428-102">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransparentDataEncryptionActivity (string name = null, string id = null, string status = null, Nullable&lt;double&gt; percentComplete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string status, valuetype System.Nullable`1&lt;float64&gt; percentComplete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.#ctor(System.String,System.String,System.String,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional status As String = null, Optional percentComplete As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity : string * string * string * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity (name, id, status, percentComplete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bd428-103">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="bd428-103">Resource name</span></span></param>
        <param name="id"><span data-ttu-id="bd428-104">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="bd428-104">The resource ID.</span></span></param>
        <param name="status"><span data-ttu-id="bd428-105">Der Status der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="bd428-105">The status of the Azure SQL database.</span></span> <span data-ttu-id="bd428-106">Folgende Werte sind möglich: "Verschlüsseln", 'Entschlüsseln'</span><span class="sxs-lookup"><span data-stu-id="bd428-106">Possible values include: 'Encrypting', 'Decrypting'</span></span></param>
        <param name="percentComplete"><span data-ttu-id="bd428-107">Der abgeschlossene Prozentsatz des transparent Data Encryption Scans für eine Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="bd428-107">The percent complete of the transparent data encryption scan for a Azure SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="bd428-108">Initialisiert eine neue Instanz der TransparentDataEncryptionActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bd428-108">Initializes a new instance of the TransparentDataEncryptionActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="bd428-109">Ruft den Prozentsatz ab des transparenten verschlüsselungsscans für eine Azure SQL-Datenbank abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="bd428-109">Gets the percent complete of the transparent data encryption scan for a Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="bd428-110">Ruft den Status der Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="bd428-110">Gets the status of the Azure SQL database.</span></span> <span data-ttu-id="bd428-111">Folgende Werte sind möglich: "Verschlüsseln", 'Entschlüsseln'</span><span class="sxs-lookup"><span data-stu-id="bd428-111">Possible values include: 'Encrypting', 'Decrypting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>