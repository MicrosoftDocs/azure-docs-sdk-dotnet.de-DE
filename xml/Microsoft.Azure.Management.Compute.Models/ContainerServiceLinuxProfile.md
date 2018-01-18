<Type Name="ContainerServiceLinuxProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceLinuxProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceLinuxProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceLinuxProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceLinuxProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dcdbb-101">Profil für virtuelle Linux-Computer im Cluster Service Container.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-101">Profile for Linux VMs in the container service cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceLinuxProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dcdbb-102">Initialisiert eine neue Instanz der ContainerServiceLinuxProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-102">Initializes a new instance of the ContainerServiceLinuxProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceLinuxProfile (string adminUsername, Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration ssh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string adminUsername, class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration ssh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (adminUsername As String, ssh As ContainerServiceSshConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile : string * Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile (adminUsername, ssh)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="ssh" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration" />
      </Parameters>
      <Docs>
        <param name="adminUsername"><span data-ttu-id="dcdbb-103">Der Benutzername des Systemadministrators für virtuelle Linux-Computer verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-103">The administrator username to use for Linux VMs.</span></span></param>
        <param name="ssh"><span data-ttu-id="dcdbb-104">Der SSH-Schlüssel Konfiguration für virtuelle Linux-Computer.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-104">The ssh key configuration for Linux VMs.</span></span></param>
        <summary>
            <span data-ttu-id="dcdbb-105">Initialisiert eine neue Instanz der ContainerServiceLinuxProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-105">Initializes a new instance of the ContainerServiceLinuxProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.AdminUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcdbb-106">Ruft ab oder legt der Administratorbenutzername, der für virtuelle Linux-Computer verwendet.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-106">Gets or sets the administrator username to use for Linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ssh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration Ssh { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration Ssh" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Ssh" />
      <MemberSignature Language="VB.NET" Value="Public Property Ssh As ContainerServiceSshConfiguration" />
      <MemberSignature Language="F#" Value="member this.Ssh : Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Ssh" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ssh")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceSshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcdbb-107">Ruft ab oder legt die SSH-Schlüssel Konfiguration für virtuelle Linux-Computer.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-107">Gets or sets the ssh key configuration for Linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceLinuxProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dcdbb-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dcdbb-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dcdbb-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dcdbb-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>