<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            die verschlüsselungseinstellungen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus encryptionStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus keyRolloverStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings (encryptionStatus, keyRolloverStatus, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encryptionStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus" />
        <Parameter Name="keyRolloverStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="encryptionStatus">Der Verschlüsselungsstatus, der angibt, ob Verschlüsselung aktiviert ist oder nicht. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="keyRolloverStatus">Der Rollover des Status, der angibt, ob der Rollover des datenverschlüsselungsschlüssels erforderlich ist. Wenn die Verschlüsselung des geheimen Schlüssels aktualisiert wurde, erfordert sie schlüsselrollovers.
            Folgende Werte sind möglich: "Erforderlich", "NotRequired"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <summary>
            Initialisiert eine neue Instanz der EncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus EncryptionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionStatus As EncryptionStatus" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.EncryptionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status der Verschlüsselung, der angibt, ob Verschlüsselung aktiviert ist oder nicht. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyRolloverStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus KeyRolloverStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyRolloverStatus As KeyRolloverStatus" />
      <MemberSignature Language="F#" Value="member this.KeyRolloverStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.KeyRolloverStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyRolloverStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.KeyRolloverStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Rollover des datenverschlüsselungsschlüssels Status gibt an, ob der Rollover des datenverschlüsselungsschlüssels erforderlich ist. Wenn die Verschlüsselung des geheimen Schlüssels aktualisiert wurde, erfordert sie schlüsselrollovers. Folgende Werte sind möglich: "Erforderlich", "NotRequired"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>