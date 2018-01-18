<Type Name="DiagnosticsProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile">
  <TypeSignature Language="C#" Value="public class DiagnosticsProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticsProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticsProfile" />
  <TypeSignature Language="F#" Value="type DiagnosticsProfile = class" />
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
            <span data-ttu-id="2a6b1-101">Beschreibt ein Diagnose-Profil an.</span><span class="sxs-lookup"><span data-stu-id="2a6b1-101">Describes a diagnostics profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a6b1-102">Initialisiert eine neue Instanz der DiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a6b1-102">Initializes a new instance of the DiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile (Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics bootDiagnostics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics bootDiagnostics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile bootDiagnostics" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics" />
      </Parameters>
      <Docs>
        <param name="bootDiagnostics"><span data-ttu-id="2a6b1-103">Startdiagnoseeinstellungen ist eine Debugfunktion, die dem Benutzer ermöglicht, die Konsolenausgabe und/oder einen Screenshot des virtuellen Computers von der Hypervisor anzeigen.</span><span class="sxs-lookup"><span data-stu-id="2a6b1-103">Boot Diagnostics is a debugging feature which allows the user to view console output and/or a screenshot of the virtual machine from the hypervisor.</span></span></param>
        <summary>
            <span data-ttu-id="2a6b1-104">Initialisiert eine neue Instanz der DiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a6b1-104">Initializes a new instance of the DiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnostics" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a6b1-105">Ermittelt oder definiert Startabbilder-Diagnose ist eine Debugfunktion die Konsolenausgabe anzeigen und/oder einen Screenshot des virtuellen Computers den Benutzer vom Hypervisor ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="2a6b1-105">Gets or sets boot Diagnostics is a debugging feature which allows the user to view console output and/or a screenshot of the virtual machine from the hypervisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>