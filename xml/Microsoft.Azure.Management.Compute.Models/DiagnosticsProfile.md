<Type Name="DiagnosticsProfile" FullName="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile">
  <TypeSignature Language="C#" Value="public class DiagnosticsProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticsProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticsProfile" />
  <TypeSignature Language="F#" Value="type DiagnosticsProfile = class" />
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
            <span data-ttu-id="ee8e6-101">Gibt den Status der Boot-diagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-101">Specifies the boot diagnostic settings state.</span></span>
            <span data-ttu-id="ee8e6-102">&lt;Brasilien&gt;&lt;Br&gt;-api-Mindestversion: 2015-06-15.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-102">&lt;br&gt;&lt;br&gt;Minimum api-version: 2015-06-15.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.#ctor" />
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
            <span data-ttu-id="ee8e6-103">Initialisiert eine neue Instanz der DiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-103">Initializes a new instance of the DiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile (Microsoft.Azure.Management.Compute.Models.BootDiagnostics bootDiagnostics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.BootDiagnostics bootDiagnostics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.#ctor(Microsoft.Azure.Management.Compute.Models.BootDiagnostics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.BootDiagnostics -&gt; Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" Usage="new Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile bootDiagnostics" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Models.BootDiagnostics" />
      </Parameters>
      <Docs>
        <param name="bootDiagnostics"><span data-ttu-id="ee8e6-104">Startdiagnoseeinstellungen ist eine Debugfunktion Dadurch haben Sie die Konsolenausgabe und Screenshot für die Diagnose von VM-Status anzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-104">Boot Diagnostics is a debugging feature which allows you to view Console Output and Screenshot to diagnose VM status.</span></span> <span data-ttu-id="ee8e6-105">&lt;Brasilien&gt;&lt;Br&gt; für virtuelle Linux-Computer, können Sie einfach die Ausgabe des Protokolls Konsole anzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-105">&lt;br&gt;&lt;br&gt; For Linux Virtual Machines, you can easily view the output of your console log.</span></span>
            <span data-ttu-id="ee8e6-106">&lt;Brasilien&gt;&lt;Br&gt; für Windows- und Linux-VMs Azure können Sie auch einen Screenshot des virtuellen Computers von der Hypervisor anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-106">&lt;br&gt;&lt;br&gt; For both Windows and Linux virtual machines, Azure also enables you to see a screenshot of the VM from the hypervisor.</span></span></param>
        <summary>
            <span data-ttu-id="ee8e6-107">Initialisiert eine neue Instanz der DiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-107">Initializes a new instance of the DiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.BootDiagnostics BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.BootDiagnostics BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnostics" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Models.BootDiagnostics with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.BootDiagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee8e6-108">Ermittelt oder definiert Startabbilder-Diagnose ist eine Debugfunktion Dadurch haben Sie die Konsolenausgabe und Screenshot für die Diagnose von VM-Status anzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-108">Gets or sets boot Diagnostics is a debugging feature which allows you to view Console Output and Screenshot to diagnose VM status.</span></span>
            <span data-ttu-id="ee8e6-109">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Für virtuelle Linux-Computer, können Sie einfach die Ausgabe des Protokolls Konsole anzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-109">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For Linux Virtual Machines, you can easily view the output of your console log.</span></span>
            <span data-ttu-id="ee8e6-110">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Für Windows- und Linux-VMs kann Azure Sie auch einen Screenshot des virtuellen Computers von der Hypervisor anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="ee8e6-110">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For both Windows and Linux virtual machines, Azure also enables you to see a screenshot of the VM from the hypervisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>