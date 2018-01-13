<Type Name="SshConfiguration" FullName="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration">
  <TypeSignature Language="C#" Value="public class SshConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SshConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class SshConfiguration" />
  <TypeSignature Language="F#" Value="type SshConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SSH-Konfigurationseinstellungen für den virtuellen Computer
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public SshConfiguration (Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, System.Collections.Generic.IList&lt;string&gt; publicIPsToAllow = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, class System.Collections.Generic.IList`1&lt;string&gt; publicIPsToAllow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.#ctor(Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.SshConfiguration : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" Usage="new Microsoft.Azure.Management.BatchAI.Models.SshConfiguration (userAccountSettings, publicIPsToAllow)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userAccountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
        <Parameter Name="publicIPsToAllow" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userAccountSettings">Einstellungen für das Benutzerkonto des virtuellen Computern.</param>
        <param name="publicIPsToAllow">Liste der Quell-IP-Adressbereiche um SSH-Verbindung zum virtuellen Computer zu ermöglichen.</param>
        <summary>
            Initialisiert eine neue Instanz der SshConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPsToAllow">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PublicIPsToAllow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PublicIPsToAllow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.PublicIPsToAllow" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPsToAllow As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PublicIPsToAllow : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.PublicIPsToAllow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicIPsToAllow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Quell-IP-Adressbereiche um SSH-Verbindung zum virtuellen Computer zu ermöglichen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Standardwert ist "*" können verwendet werden, um alle Quell-IP-Adressen übereinstimmen. Maximale Anzahl von PublicIPs, die angegeben werden können, sind 400.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.UserAccountSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccountSettings As UserAccountSettings" />
      <MemberSignature Language="F#" Value="member this.UserAccountSettings : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.UserAccountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userAccountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Einstellungen für das Benutzerkonto des virtuellen Computern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SshConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sshConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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