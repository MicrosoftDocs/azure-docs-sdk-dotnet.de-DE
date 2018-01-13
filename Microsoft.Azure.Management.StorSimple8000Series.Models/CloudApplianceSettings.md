<Type Name="CloudApplianceSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings">
  <TypeSignature Language="C#" Value="public class CloudApplianceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudApplianceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudApplianceSettings" />
  <TypeSignature Language="F#" Value="type CloudApplianceSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Einstellungen für den Cloud-Anwendung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloudApplianceSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret serviceDataEncryptionKey = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret channelIntegrityKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret serviceDataEncryptionKey, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret channelIntegrityKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceDataEncryptionKey As AsymmetricEncryptedSecret = null, Optional channelIntegrityKey As AsymmetricEncryptedSecret = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings (serviceDataEncryptionKey, channelIntegrityKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceDataEncryptionKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="channelIntegrityKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
      </Parameters>
      <Docs>
        <param name="serviceDataEncryptionKey">Der Verschlüsselungsschlüssel für Dienstdaten (mit DAK verschlüsselt).</param>
        <param name="channelIntegrityKey">Der Kanal Integrität Schlüssel (mit DAK verschlüsselt).</param>
        <summary>
            Initialisiert eine neue Instanz der CloudApplianceSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelIntegrityKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ChannelIntegrityKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ChannelIntegrityKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ChannelIntegrityKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelIntegrityKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.ChannelIntegrityKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ChannelIntegrityKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="channelIntegrityKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Kanal Integrität-Schlüssel (verschlüsselt mit DAK) fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDataEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ServiceDataEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ServiceDataEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ServiceDataEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDataEncryptionKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.ServiceDataEncryptionKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ServiceDataEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceDataEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest (verschlüsselten mit DAK) der Dienstdaten-Verschlüsselungsschlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudApplianceSettings.Validate " />
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