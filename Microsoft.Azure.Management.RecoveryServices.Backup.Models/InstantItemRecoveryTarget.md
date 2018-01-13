<Type Name="InstantItemRecoveryTarget" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget">
  <TypeSignature Language="C#" Value="public class InstantItemRecoveryTarget" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InstantItemRecoveryTarget extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget" />
  <TypeSignature Language="VB.NET" Value="Public Class InstantItemRecoveryTarget" />
  <TypeSignature Language="F#" Value="type InstantItemRecoveryTarget = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ef62-101">Zieldetails für die Datei / Ordner wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="2ef62-101">Target details for file / folder restore.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstantItemRecoveryTarget ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ef62-102">Initialisiert eine neue Instanz der InstantItemRecoveryTarget-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ef62-102">Initializes a new instance of the InstantItemRecoveryTarget class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstantItemRecoveryTarget (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; clientScripts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; clientScripts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientScripts As IList(Of ClientScriptForConnect) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget clientScripts" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientScripts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt;" />
      </Parameters>
      <Docs>
        <param name="clientScripts"><span data-ttu-id="2ef62-103">Liste der Clientskripts.</span><span class="sxs-lookup"><span data-stu-id="2ef62-103">List of client scripts.</span></span></param>
        <summary>
            <span data-ttu-id="2ef62-104">Initialisiert eine neue Instanz der InstantItemRecoveryTarget-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ef62-104">Initializes a new instance of the InstantItemRecoveryTarget class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientScripts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; ClientScripts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; ClientScripts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget.ClientScripts" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientScripts As IList(Of ClientScriptForConnect)" />
      <MemberSignature Language="F#" Value="member this.ClientScripts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget.ClientScripts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientScripts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientScriptForConnect&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ef62-105">Ruft ab oder Liste von Clientskripts fest.</span><span class="sxs-lookup"><span data-stu-id="2ef62-105">Gets or sets list of client scripts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>