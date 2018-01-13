<Type Name="DeletedKeyItem" FullName="Microsoft.Azure.KeyVault.Models.DeletedKeyItem">
  <TypeSignature Language="C#" Value="public class DeletedKeyItem : Microsoft.Azure.KeyVault.Models.KeyItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedKeyItem extends Microsoft.Azure.KeyVault.Models.KeyItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.DeletedKeyItem" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedKeyItem&#xA;Inherits KeyItem" />
  <TypeSignature Language="F#" Value="type DeletedKeyItem = class&#xA;    inherit KeyItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.KeyItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Das gelöschte Key-Element mit den gelöschten Metadaten und Informationen zu löschen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DeletedKeyItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyItem (string kid = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; managed = null, string recoveryId = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, Nullable&lt;DateTime&gt; deletedDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kid, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; managed, string recoveryId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.#ctor(System.String,Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional kid As String = null, Optional attributes As KeyAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional managed As Nullable(Of Boolean) = null, Optional recoveryId As String = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional deletedDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.DeletedKeyItem : string * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.DeletedKeyItem" Usage="new Microsoft.Azure.KeyVault.Models.DeletedKeyItem (kid, attributes, tags, managed, recoveryId, scheduledPurgeDate, deletedDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="kid">Der Schlüsselbezeichner.</param>
        <param name="attributes">Die schlüsselverwaltung-Attribute.</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <param name="managed">"True", wenn der Schlüssel Lebensdauer von schlüsseltresor verwaltet wird. Ist dies ein Schlüssel sichern wird ein Zertifikat, klicken Sie dann verwalteten "true" sein.</param>
        <param name="recoveryId">Die Url der Recovery-Objekt, zum Identifizieren und Wiederherstellen des gelöschten Schlüssels verwendet.</param>
        <param name="scheduledPurgeDate">Die Zeit, wenn des Schlüssels geplant wurde, gelöscht werden, (UTC)</param>
        <param name="deletedDate">Die Zeit, wenn der Schlüssel gelöscht wurde, (UTC)</param>
        <summary>
            Initialisiert eine neue Instanz der DeletedKeyItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.DeletedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyItem.DeletedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deletedDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit, wenn der Schlüssel, in UTC gelöscht wurde, ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryId">
      <MemberSignature Language="C#" Value="public string RecoveryId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.RecoveryId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyItem.RecoveryId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Url der Recovery-Objekt, zum Identifizieren und Wiederherstellen des gelöschten Schlüssels verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.DeletedKeyIdentifier RecoveryIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.DeletedKeyIdentifier RecoveryIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.RecoveryIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryIdentifier As DeletedKeyIdentifier" />
      <MemberSignature Language="F#" Value="member this.RecoveryIdentifier : Microsoft.Azure.KeyVault.DeletedKeyIdentifier" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyItem.RecoveryIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.DeletedKeyIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Bezeichner des gelöschten Schlüsselobjekts. Dient zum Wiederherstellen des Schlüssels.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyItem.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyItem.ScheduledPurgeDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduledPurgeDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit, wenn des Schlüssels geplant wurde, gelöscht werden, in UTC, ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>