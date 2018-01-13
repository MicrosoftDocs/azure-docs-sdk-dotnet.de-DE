<Type Name="ClientScriptForConnect" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect">
  <TypeSignature Language="C#" Value="public class ClientScriptForConnect" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientScriptForConnect extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientScriptForConnect" />
  <TypeSignature Language="F#" Value="type ClientScriptForConnect = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="af990-101">Details zum Client-Skript für die Datei / Ordner wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="af990-101">Client script details for file / folder restore.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af990-102">Initialisiert eine neue Instanz der ClientScriptForConnect-Klasse.</span><span class="sxs-lookup"><span data-stu-id="af990-102">Initializes a new instance of the ClientScriptForConnect class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientScriptForConnect (string scriptContent = null, string scriptExtension = null, string osType = null, string url = null, string scriptNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scriptContent, string scriptExtension, string osType, string url, string scriptNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scriptContent As String = null, Optional scriptExtension As String = null, Optional osType As String = null, Optional url As String = null, Optional scriptNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect (scriptContent, scriptExtension, osType, url, scriptNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scriptContent" Type="System.String" />
        <Parameter Name="scriptExtension" Type="System.String" />
        <Parameter Name="osType" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="scriptNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scriptContent"><span data-ttu-id="af990-103">Datei Inhalt des Clientskripts für die Datei / Ordner wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="af990-103">File content of the client script for file / folder restore.</span></span></param>
        <param name="scriptExtension"><span data-ttu-id="af990-104">Die Dateierweiterung des Clientskripts für die Datei / Ordner wiederherstellen –. ps1 "," sh "" usw.</span><span class="sxs-lookup"><span data-stu-id="af990-104">File extension of the client script for file / folder restore - .ps1 , .sh , etc.</span></span></param>
        <param name="osType"><span data-ttu-id="af990-105">BS-Typ – Windows, Linux usw. für die diese Datei / Ordner Client Wiederherstellungsskript funktioniert.</span><span class="sxs-lookup"><span data-stu-id="af990-105">OS type - Windows, Linux etc. for which this file / folder restore client script works.</span></span></param>
        <param name="url"><span data-ttu-id="af990-106">URL der ausführbare Datei aus, aus der Quelle des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="af990-106">URL of Executable from where to source the content.</span></span> <span data-ttu-id="af990-107">Wenn dies nicht null ist sollte dann ScriptContent nicht verwendet werden</span><span class="sxs-lookup"><span data-stu-id="af990-107">If this is not null then ScriptContent should not be used</span></span></param>
        <param name="scriptNameSuffix"><span data-ttu-id="af990-108">Mandator-Suffix, das den Namen des Skripts hinzugefügt werden sollen, die zum Herunterladen als Benutzer gewährt wird.</span><span class="sxs-lookup"><span data-stu-id="af990-108">Mandator suffix that should be added to the name of script that is given for download to user.</span></span>
            <span data-ttu-id="af990-109">Wenn die Null oder leer, nicht jedoch.</span><span class="sxs-lookup"><span data-stu-id="af990-109">If its null or empty then , ignore it.</span></span></param>
        <summary>
            <span data-ttu-id="af990-110">Initialisiert eine neue Instanz der ClientScriptForConnect-Klasse.</span><span class="sxs-lookup"><span data-stu-id="af990-110">Initializes a new instance of the ClientScriptForConnect class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af990-111">Ruft ab oder legt ihn fest BS-Typ – Windows, Linux usw. für die diese Datei / Ordner Client Wiederherstellungsskript funktioniert.</span><span class="sxs-lookup"><span data-stu-id="af990-111">Gets or sets OS type - Windows, Linux etc. for which this file / folder restore client script works.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptContent">
      <MemberSignature Language="C#" Value="public string ScriptContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptContent As String" />
      <MemberSignature Language="F#" Value="member this.ScriptContent : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af990-112">Ruft ab oder legt ihn fest Dateiinhalt des Clientskripts für die Datei / Ordner wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="af990-112">Gets or sets file content of the client script for file / folder restore.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptExtension">
      <MemberSignature Language="C#" Value="public string ScriptExtension { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptExtension" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptExtension As String" />
      <MemberSignature Language="F#" Value="member this.ScriptExtension : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptExtension" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptExtension")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af990-113">Ruft ab oder legt ihn fest-Erweiterung von Clientskripts für die Datei / Ordner wiederherstellen –. ps1 "," sh "" usw.</span><span class="sxs-lookup"><span data-stu-id="af990-113">Gets or sets file extension of the client script for file / folder restore - .ps1 , .sh , etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptNameSuffix">
      <MemberSignature Language="C#" Value="public string ScriptNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.ScriptNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.ScriptNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af990-114">Ruft ab, oder legt ihn fest Mandator-Suffix, das den Namen des Skripts hinzugefügt werden sollen, die zum Herunterladen als Benutzer gewährt wird.</span><span class="sxs-lookup"><span data-stu-id="af990-114">Gets or sets mandator suffix that should be added to the name of script that is given for download to user.</span></span>
            <span data-ttu-id="af990-115">Wenn die Null oder leer, nicht jedoch.</span><span class="sxs-lookup"><span data-stu-id="af990-115">If its null or empty then , ignore it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af990-116">Abrufen oder Festlegen der URL der ausführbaren Datei, an der Quelle des Inhalts.</span><span class="sxs-lookup"><span data-stu-id="af990-116">Gets or sets URL of Executable from where to source the content.</span></span> <span data-ttu-id="af990-117">Wenn dies nicht null ist sollte dann ScriptContent nicht verwendet werden</span><span class="sxs-lookup"><span data-stu-id="af990-117">If this is not null then ScriptContent should not be used</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>