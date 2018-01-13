<Type Name="SshConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration">
  <TypeSignature Language="C#" Value="public class SshConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SshConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class SshConfiguration" />
  <TypeSignature Language="F#" Value="type SshConfiguration = class" />
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
            SSH-Konfiguration für Linux-basierten virtuellen Computer auf Azure
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SshConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; publicKeys = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; publicKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publicKeys As IList(Of SshPublicKey) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration publicKeys" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publicKeys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt;" />
      </Parameters>
      <Docs>
        <param name="publicKeys">Die Liste der öffentlichen SSH-Schlüssel verwendet, um die Authentifizierung mit Linux basieren VMs.</param>
        <summary>
            Initialisiert eine neue Instanz der SshConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; PublicKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; PublicKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration.PublicKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicKeys As IList(Of SshPublicKey)" />
      <MemberSignature Language="F#" Value="member this.PublicKeys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SshConfiguration.PublicKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der öffentlichen SSH-Schlüssel zur Authentifizierung mit Linux-basierten virtuellen Computern herstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>