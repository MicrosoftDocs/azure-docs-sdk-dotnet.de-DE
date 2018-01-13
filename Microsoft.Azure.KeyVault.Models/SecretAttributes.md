<Type Name="SecretAttributes" FullName="Microsoft.Azure.KeyVault.Models.SecretAttributes">
  <TypeSignature Language="C#" Value="public class SecretAttributes : Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecretAttributes extends Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SecretAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Class SecretAttributes&#xA;Inherits Attributes" />
  <TypeSignature Language="F#" Value="type SecretAttributes = class&#xA;    inherit Attributes" />
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
            Die Attribute für den geheimen Management.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretAttributes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretAttributes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SecretAttributes-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretAttributes (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; notBefore = null, Nullable&lt;DateTime&gt; expires = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null, string recoveryLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notBefore, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expires, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated, string recoveryLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretAttributes.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional notBefore As Nullable(Of DateTime) = null, Optional expires As Nullable(Of DateTime) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null, Optional recoveryLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SecretAttributes : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.KeyVault.Models.SecretAttributes" Usage="new Microsoft.Azure.KeyVault.Models.SecretAttributes (enabled, notBefore, expires, created, updated, recoveryLevel)" />
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
        <param name="enabled">Bestimmt, ob das Objekt aktiviert ist.</param>
        <param name="notBefore">Nicht vor dem Datum in UTC.</param>
        <param name="expires">Ablaufdatum in UTC.</param>
        <param name="created">Der Erstellungszeitpunkt (UTC).</param>
        <param name="updated">Letzte aktualisierte Zeit in UTC.</param>
        <param name="recoveryLevel">Gibt die Löschung Recovery Ebene derzeit wirksamen für geheime Schlüssel im aktuellen Tresor wieder. Wenn sie "Purgeable" enthält, kann der geheime Schlüssel von einem privilegierten Benutzer dauerhaft gelöscht; Andernfalls kann nur das System den geheimen Hauptschlüssel am Ende das beibehaltungsintervall löschen. Folgende Werte sind möglich: "Purgeable", "Behebbarer + Purgeable", "Wiederherstellbar", "Behebbarer + ProtectedSubscription"</param>
        <summary>
            Initialisiert eine neue Instanz der SecretAttributes-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryLevel">
      <MemberSignature Language="C#" Value="public string RecoveryLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretAttributes.RecoveryLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryLevel As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryLevel : string" Usage="Microsoft.Azure.KeyVault.Models.SecretAttributes.RecoveryLevel" />
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
            Ruft gibt die Löschung Recovery Ebene derzeit wirksamen für geheime Schlüssel im aktuellen Tresor wieder. Wenn sie "Purgeable" enthält, kann der geheime Schlüssel von einem privilegierten Benutzer dauerhaft gelöscht; Andernfalls kann nur das System den geheimen Hauptschlüssel am Ende das beibehaltungsintervall löschen. Folgende Werte sind möglich: "Purgeable", "Behebbarer + Purgeable", "Wiederherstellbar", "Behebbarer + ProtectedSubscription"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>