<Type Name="SnapshotRecoveryRequest" FullName="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest">
  <TypeSignature Language="C#" Value="public class SnapshotRecoveryRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SnapshotRecoveryRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class SnapshotRecoveryRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SnapshotRecoveryRequest = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ca540-101">Details zur app-Wiederherstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="ca540-101">Details about app recovery operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotRecoveryRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca540-102">Initialisiert eine neue Instanz der SnapshotRecoveryRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ca540-102">Initializes a new instance of the SnapshotRecoveryRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotRecoveryRequest (string id = null, string name = null, string kind = null, string type = null, string snapshotTime = null, Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget recoveryTarget = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;bool&gt; recoverConfiguration = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string snapshotTime, class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget recoveryTarget, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;bool&gt; recoverConfiguration, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional snapshotTime As String = null, Optional recoveryTarget As SnapshotRecoveryTarget = null, Optional overwrite As Nullable(Of Boolean) = null, Optional recoverConfiguration As Nullable(Of Boolean) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest : string * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest (id, name, kind, type, snapshotTime, recoveryTarget, overwrite, recoverConfiguration, ignoreConflictingHostNames)" />
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
        <Parameter Name="snapshotTime" Type="System.String" />
        <Parameter Name="recoveryTarget" Type="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoverConfiguration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="ca540-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="ca540-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="ca540-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="ca540-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="ca540-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ca540-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="ca540-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="ca540-106">Resource type.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="ca540-107">Zeigen Sie Zeit, in dem die app-Wiederherstellung soll als DateTime-Zeichenfolge formatiert versucht werden, ein.</span><span class="sxs-lookup"><span data-stu-id="ca540-107">Point in time in which the app recovery should be attempted, formatted as a DateTime string.</span></span></param>
        <param name="recoveryTarget"><span data-ttu-id="ca540-108">Gibt die Web-app, der momentaufnahmeinhalt geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="ca540-108">Specifies the web app that snapshot contents will be written to.</span></span></param>
        <param name="overwrite"><span data-ttu-id="ca540-109">Wenn &lt;Code&gt;"true"&lt;/code&gt; Wiederherstellungsvorgang Quelle-app kann überschrieben werden kann, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="ca540-109">If &lt;code&gt;true&lt;/code&gt; the recovery operation can overwrite source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="recoverConfiguration"><span data-ttu-id="ca540-110">Bei "true", wird zusätzlich zum Inhalt, der Standort-Konfiguration wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="ca540-110">If true, site configuration, in addition to content, will be reverted.</span></span></param>
        <param name="ignoreConflictingHostNames"><span data-ttu-id="ca540-111">Bei "true", werden benutzerdefinierte Hostnamen Konflikte bei der postfachwiederherstellung in einer Web-app Ziel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ca540-111">If true, custom hostname conflicts will be ignored when recovering to a target web app.</span></span>
            <span data-ttu-id="ca540-112">Diese Einstellung ist nur erforderlich, wenn die RecoverConfiguration aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ca540-112">This setting is only necessary when RecoverConfiguration is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="ca540-113">Initialisiert eine neue Instanz der SnapshotRecoveryRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ca540-113">Initializes a new instance of the SnapshotRecoveryRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca540-114">Ruft ab oder legt fest, wenn "true" werden benutzerdefinierte Hostnamen Konflikte ignoriert werden, bei der postfachwiederherstellung in eine Ziel-Web-app.</span><span class="sxs-lookup"><span data-stu-id="ca540-114">Gets or sets if true, custom hostname conflicts will be ignored when recovering to a target web app.</span></span>
            <span data-ttu-id="ca540-115">Diese Einstellung ist nur erforderlich, wenn die RecoverConfiguration aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ca540-115">This setting is only necessary when RecoverConfiguration is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca540-116">Ruft ab oder legt sie fest, wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wiederherstellungsvorgang Quelle-app kann überschrieben werden kann, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="ca540-116">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; the recovery operation can overwrite source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverConfiguration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RecoverConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RecoverConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoverConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoverConfiguration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RecoverConfiguration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoverConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoverConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca540-117">Ruft ab oder legt fest, wenn "true" Standortkonfiguration neben Inhalt, werden zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="ca540-117">Gets or sets if true, site configuration, in addition to content, will be reverted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryTarget">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget RecoveryTarget { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget RecoveryTarget" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoveryTarget" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryTarget As SnapshotRecoveryTarget" />
      <MemberSignature Language="F#" Value="member this.RecoveryTarget : Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoveryTarget" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryTarget")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca540-118">Gibt an die Web-app, der momentaufnahmeinhalt geschrieben werden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="ca540-118">Gets or sets specifies the web app that snapshot contents will be written to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public string SnapshotTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotTime As String" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca540-119">Ruft ab oder legt fest, zeigen Sie in der die app-Wiederherstellung soll als DateTime-Zeichenfolge formatiert versucht werden.</span><span class="sxs-lookup"><span data-stu-id="ca540-119">Gets or sets point in time in which the app recovery should be attempted, formatted as a DateTime string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>