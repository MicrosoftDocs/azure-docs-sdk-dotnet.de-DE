<Type Name="DataLakeAnalyticsCatalogCredentialUpdateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsCatalogCredentialUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsCatalogCredentialUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsCatalogCredentialUpdateParameters" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsCatalogCredentialUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1131-101">Data Lake Analytics-Katalog Update Anmeldeparameter.</span><span class="sxs-lookup"><span data-stu-id="d1131-101">Data Lake Analytics catalog credential update parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1131-102">Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1131-102">Initializes a new instance of the DataLakeAnalyticsCatalogCredentialUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialUpdateParameters (string password = null, string newPassword = null, string uri = null, string userId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, string newPassword, string uri, string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional password As String = null, Optional newPassword As String = null, Optional uri As String = null, Optional userId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters : string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters (password, newPassword, uri, userId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="newPassword" Type="System.String" />
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password"><span data-ttu-id="d1131-103">das aktuelle Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="d1131-103">the current password for the credential and user with access to the data source.</span></span> <span data-ttu-id="d1131-104">Dies ist erforderlich, wenn der Antragsteller nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="d1131-104">This is required if the requester is not the account owner.</span></span></param>
        <param name="newPassword"><span data-ttu-id="d1131-105">das neue Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="d1131-105">the new password for the credential and user with access to the data source.</span></span></param>
        <param name="uri"><span data-ttu-id="d1131-106">Der URI-Bezeichner für die Datenquelle diese Anmeldeinformationen zum Verbinden kann, im Format &lt;Hostname&gt;:&lt;Port&gt;</span><span class="sxs-lookup"><span data-stu-id="d1131-106">the URI identifier for the data source this credential can connect to in the format &lt;hostname&gt;:&lt;port&gt;</span></span></param>
        <param name="userId"><span data-ttu-id="d1131-107">die Objekt-ID für den Benutzer, der diesen Anmeldeinformationen mit Zugriff auf die Datenquelle zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d1131-107">the object identifier for the user associated with this credential with access to the data source.</span></span></param>
        <summary>
            <span data-ttu-id="d1131-108">Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1131-108">Initializes a new instance of the DataLakeAnalyticsCatalogCredentialUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewPassword">
      <MemberSignature Language="C#" Value="public string NewPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NewPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.NewPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property NewPassword As String" />
      <MemberSignature Language="F#" Value="member this.NewPassword : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.NewPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="newPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1131-109">Ruft ab oder legt das neue Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="d1131-109">Gets or sets the new password for the credential and user with access to the data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1131-110">Ruft ab oder legt das aktuelle Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="d1131-110">Gets or sets the current password for the credential and user with access to the data source.</span></span> <span data-ttu-id="d1131-111">Dies ist erforderlich, wenn der Antragsteller nicht Besitzer des Kontos ist.</span><span class="sxs-lookup"><span data-stu-id="d1131-111">This is required if the requester is not the account owner.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1131-112">Ruft ab oder legt Sie in das Format den URI-Bezeichner für die Datenquelle dieser Anmeldeinformationen eine zum Verbindung &amp;Lt; Hostname&amp;Gt;:&amp;Lt; Port&amp;Gt;</span><span class="sxs-lookup"><span data-stu-id="d1131-112">Gets or sets the URI identifier for the data source this credential can connect to in the format &amp;lt;hostname&amp;gt;:&amp;lt;port&amp;gt;</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1131-113">Ruft ab oder legt die Objekt-ID für den Benutzer, der diesen Anmeldeinformationen mit Zugriff auf die Datenquelle zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d1131-113">Gets or sets the object identifier for the user associated with this credential with access to the data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>