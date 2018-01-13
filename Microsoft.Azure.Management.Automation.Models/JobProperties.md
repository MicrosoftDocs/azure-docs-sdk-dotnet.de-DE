<Type Name="JobProperties" FullName="Microsoft.Azure.Management.Automation.Models.JobProperties">
  <TypeSignature Language="C#" Value="public class JobProperties : Microsoft.Azure.Management.Automation.Models.JobPropertiesBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobProperties extends Microsoft.Azure.Management.Automation.Models.JobPropertiesBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobProperties&#xA;Inherits JobPropertiesBase" />
  <TypeSignature Language="F#" Value="type JobProperties = class&#xA;    inherit JobPropertiesBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Automation.Models.JobPropertiesBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c46fa-101">Definition der Auftragseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="c46fa-101">Definition of job properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c46fa-102">Initialisiert eine neue Instanz der JobProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c46fa-102">Initializes a new instance of the JobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.Runbook" />
      <MemberSignature Language="VB.NET" Value="Public Property Runbook As RunbookAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Runbook : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.Runbook" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c46fa-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="c46fa-103">Optional.</span></span> <span data-ttu-id="c46fa-104">Ruft ab oder legt das Runbook.</span><span class="sxs-lookup"><span data-stu-id="c46fa-104">Gets or sets the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.RunOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c46fa-105">Optional.</span><span class="sxs-lookup"><span data-stu-id="c46fa-105">Optional.</span></span> <span data-ttu-id="c46fa-106">Abrufen oder Festlegen der RunOn der angibt, den Gruppennamen ist, in dem der Auftrag ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="c46fa-106">Gets or sets the runOn which specifies the group name where the job is to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartedBy">
      <MemberSignature Language="C#" Value="public string StartedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.StartedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property StartedBy As String" />
      <MemberSignature Language="F#" Value="member this.StartedBy : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.StartedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c46fa-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="c46fa-107">Optional.</span></span> <span data-ttu-id="c46fa-108">Abrufen oder festlegen den Auftrag gestartet.</span><span class="sxs-lookup"><span data-stu-id="c46fa-108">Gets or sets the job started by.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>