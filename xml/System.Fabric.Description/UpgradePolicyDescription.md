<Type Name="UpgradePolicyDescription" FullName="System.Fabric.Description.UpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public abstract class UpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit UpgradePolicyDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class UpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type UpgradePolicyDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="058d7-101">Beschreibt die Upgraderichtlinie des Diensts an.</span><span class="sxs-lookup"><span data-stu-id="058d7-101">Describes the upgrade policy of the service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected UpgradePolicyDescription (System.Fabric.Description.UpgradeKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.UpgradeKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UpgradePolicyDescription.#ctor(System.Fabric.Description.UpgradeKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As UpgradeKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UpgradePolicyDescription : System.Fabric.Description.UpgradeKind -&gt; System.Fabric.Description.UpgradePolicyDescription" Usage="new System.Fabric.Description.UpgradePolicyDescription kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Description.UpgradeKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>
            <span data-ttu-id="058d7-102"><see cref="T:System.Fabric.Description.UpgradeKind" />: Beschreibt die Art des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="058d7-102"><see cref="T:System.Fabric.Description.UpgradeKind" />: Describes the kind of upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="058d7-103">Initialisiert eine Instanz von der <see cref="T:System.Fabric.Description.UpgradePolicyDescription" /> -Klasse mit der Art des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="058d7-103">Initializes an instance of the <see cref="T:System.Fabric.Description.UpgradePolicyDescription" /> class with the upgrade kind.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.UpgradeKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradePolicyDescription.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As UpgradeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Description.UpgradeKind" Usage="System.Fabric.Description.UpgradePolicyDescription.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="058d7-104">Ruft die Art des Anwendungsupgrades ab.</span><span class="sxs-lookup"><span data-stu-id="058d7-104">Gets the kind of application upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="058d7-105">Die <see cref="T:System.Fabric.Description.UpgradeKind" /> des Anwendungsupgrades.</span><span class="sxs-lookup"><span data-stu-id="058d7-105">The <see cref="T:System.Fabric.Description.UpgradeKind" /> of the application upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>