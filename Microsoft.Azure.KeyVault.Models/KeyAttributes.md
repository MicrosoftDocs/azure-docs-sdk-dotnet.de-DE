<Type Name="KeyAttributes" FullName="Microsoft.Azure.KeyVault.Models.KeyAttributes">
  <TypeSignature Language="C#" Value="public class KeyAttributes : Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyAttributes extends Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyAttributes&#xA;Inherits Attributes" />
  <TypeSignature Language="F#" Value="type KeyAttributes = class&#xA;    inherit Attributes" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.Attributes</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0b723-101">Die Attribute eines Schlüssels, der von der schlüsseltresordienst verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="0b723-101">The attributes of a key managed by the key vault service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAttributes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyAttributes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0b723-102">Initialisiert eine neue Instanz der KeyAttributes-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b723-102">Initializes a new instance of the KeyAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAttributes (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; notBefore = null, Nullable&lt;DateTime&gt; expires = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null, string recoveryLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notBefore, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expires, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated, string recoveryLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyAttributes.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional notBefore As Nullable(Of DateTime) = null, Optional expires As Nullable(Of DateTime) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null, Optional recoveryLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyAttributes : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.KeyVault.Models.KeyAttributes" Usage="new Microsoft.Azure.KeyVault.Models.KeyAttributes (enabled, notBefore, expires, created, updated, recoveryLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="notBefore" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expires" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="0b723-103">Bestimmt, ob das Objekt aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="0b723-103">Determines whether the object is enabled.</span></span></param>
        <param name="notBefore"><span data-ttu-id="0b723-104">Nicht vor dem Datum in UTC.</span><span class="sxs-lookup"><span data-stu-id="0b723-104">Not before date in UTC.</span></span></param>
        <param name="expires"><span data-ttu-id="0b723-105">Ablaufdatum in UTC.</span><span class="sxs-lookup"><span data-stu-id="0b723-105">Expiry date in UTC.</span></span></param>
        <param name="created"><span data-ttu-id="0b723-106">Der Erstellungszeitpunkt (UTC).</span><span class="sxs-lookup"><span data-stu-id="0b723-106">Creation time in UTC.</span></span></param>
        <param name="updated"><span data-ttu-id="0b723-107">Letzte aktualisierte Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="0b723-107">Last updated time in UTC.</span></span></param>
        <param name="recoveryLevel"><span data-ttu-id="0b723-108">Gibt die löschen Recovery Ebene derzeit wirksamen für Schlüssel im aktuellen Tresor wieder.</span><span class="sxs-lookup"><span data-stu-id="0b723-108">Reflects the deletion recovery level currently in effect for keys in the current vault.</span></span> <span data-ttu-id="0b723-109">Wenn sie "Purgeable" enthält kann der Schlüssel von einem privilegierten Benutzer endgültig gelöscht werden; Andernfalls kann nur das System den Schlüssel am Ende das beibehaltungsintervall löschen.</span><span class="sxs-lookup"><span data-stu-id="0b723-109">If it contains 'Purgeable' the key can be permanently deleted by a privileged user; otherwise, only the system can purge the key, at the end of the retention interval.</span></span> <span data-ttu-id="0b723-110">Folgende Werte sind möglich: "Purgeable", "Behebbarer + Purgeable", "Wiederherstellbar", "Behebbarer + ProtectedSubscription"</span><span class="sxs-lookup"><span data-stu-id="0b723-110">Possible values include: 'Purgeable', 'Recoverable+Purgeable', 'Recoverable', 'Recoverable+ProtectedSubscription'</span></span></param>
        <summary>
            <span data-ttu-id="0b723-111">Initialisiert eine neue Instanz der KeyAttributes-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b723-111">Initializes a new instance of the KeyAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryLevel">
      <MemberSignature Language="C#" Value="public string RecoveryLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyAttributes.RecoveryLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryLevel As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryLevel : string" Usage="Microsoft.Azure.KeyVault.Models.KeyAttributes.RecoveryLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b723-112">Ruft widerspiegelt löschen Wiederherstellung die Ebene des derzeit wirksamen für Schlüssel im aktuellen Tresor.</span><span class="sxs-lookup"><span data-stu-id="0b723-112">Gets reflects the deletion recovery level currently in effect for keys in the current vault.</span></span> <span data-ttu-id="0b723-113">Wenn sie "Purgeable" enthält kann der Schlüssel von einem privilegierten Benutzer endgültig gelöscht werden; Andernfalls kann nur das System den Schlüssel am Ende das beibehaltungsintervall löschen.</span><span class="sxs-lookup"><span data-stu-id="0b723-113">If it contains 'Purgeable' the key can be permanently deleted by a privileged user; otherwise, only the system can purge the key, at the end of the retention interval.</span></span>
            <span data-ttu-id="0b723-114">Folgende Werte sind möglich: "Purgeable", "Behebbarer + Purgeable", "Wiederherstellbar", "Behebbarer + ProtectedSubscription"</span><span class="sxs-lookup"><span data-stu-id="0b723-114">Possible values include: 'Purgeable', 'Recoverable+Purgeable', 'Recoverable', 'Recoverable+ProtectedSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>