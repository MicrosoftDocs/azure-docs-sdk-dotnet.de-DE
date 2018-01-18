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
            <span data-ttu-id="ae667-101">SSH-Konfigurationseinstellungen für den virtuellen Computer</span><span class="sxs-lookup"><span data-stu-id="ae667-101">SSH configuration settings for the VM</span></span>
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
            <span data-ttu-id="ae667-102">Initialisiert eine neue Instanz der SshConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ae667-102">Initializes a new instance of the SshConfiguration class.</span></span>
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
        <param name="userAccountSettings"><span data-ttu-id="ae667-103">Einstellungen für das Benutzerkonto des virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="ae667-103">Settings for user account of VMs.</span></span></param>
        <param name="publicIPsToAllow"><span data-ttu-id="ae667-104">Liste der Quell-IP-Adressbereiche um SSH-Verbindung zum virtuellen Computer zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="ae667-104">List of source IP ranges to allow SSH connection to VM.</span></span></param>
        <summary>
            <span data-ttu-id="ae667-105">Initialisiert eine neue Instanz der SshConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ae667-105">Initializes a new instance of the SshConfiguration class.</span></span>
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
            <span data-ttu-id="ae667-106">Ruft ab oder legt die Liste der Quell-IP-Adressbereiche um SSH-Verbindung zum virtuellen Computer zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="ae667-106">Gets or sets list of source IP ranges to allow SSH connection to VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ae667-107">Standardwert ist "\*" können verwendet werden, um alle Quell-IP-Adressen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ae667-107">Default value is '\*' can be used to match all source IPs.</span></span> <span data-ttu-id="ae667-108">Maximale Anzahl von PublicIPs, die angegeben werden können, sind 400.</span><span class="sxs-lookup"><span data-stu-id="ae667-108">Maximum number of publicIPs that can be specified are 400.</span></span>
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
            <span data-ttu-id="ae667-109">Ruft ab, oder legt ihn fest-Einstellungen für das Benutzerkonto des virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="ae667-109">Gets or sets settings for user account of VMs.</span></span>
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
            <span data-ttu-id="ae667-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ae667-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ae667-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ae667-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>