<Type Name="KeyVaultKeyReference" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference">
  <TypeSignature Language="C#" Value="public class KeyVaultKeyReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultKeyReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultKeyReference" />
  <TypeSignature Language="F#" Value="type KeyVaultKeyReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt einen Verweis auf die Key Vault-Schlüssels
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultKeyReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultKeyReference (string keyUrl, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyUrl, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.#ctor(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyUrl As String, sourceVault As SubResource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference : string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference (keyUrl, sourceVault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyUrl" Type="System.String" />
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
      </Parameters>
      <Docs>
        <param name="keyUrl">Die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.</param>
        <param name="sourceVault">Die relative URL des Tresors Schlüssel mit dem Schlüssel.</param>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultKeyReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL verweisen auf einen Schlüssel in einem Schlüsseltresor.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die relative URL des Schlüsseltresor mit dem Schlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultKeyReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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