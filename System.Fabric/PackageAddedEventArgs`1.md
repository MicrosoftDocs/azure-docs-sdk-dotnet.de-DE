<Type Name="PackageAddedEventArgs&lt;TPackage&gt;" FullName="System.Fabric.PackageAddedEventArgs&lt;TPackage&gt;">
  <TypeSignature Language="C#" Value="public sealed class PackageAddedEventArgs&lt;TPackage&gt; : EventArgs where TPackage : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PackageAddedEventArgs`1&lt;class TPackage&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageAddedEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PackageAddedEventArgs(Of TPackage)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type PackageAddedEventArgs&lt;'Package (requires 'Package : null)&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TPackage">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Small class.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="TPackage">
      <para><span data-ttu-id="b3989-101">Der Typ des Pakets beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="b3989-101">Type of the package being described.</span></span> <span data-ttu-id="b3989-102">Finden Sie unter <see cref="T:System.Fabric.CodePackage" />, <see cref="T:System.Fabric.ConfigurationPackage" />, <see cref="T:System.Fabric.DataPackage" />.</span><span class="sxs-lookup"><span data-stu-id="b3989-102">See <see cref="T:System.Fabric.CodePackage" />, <see cref="T:System.Fabric.ConfigurationPackage" />, <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
    </typeparam>
    <summary>
      <para><span data-ttu-id="b3989-103">Beschreibt eine hinzugefügte Ereignis des Pakets an.</span><span class="sxs-lookup"><span data-stu-id="b3989-103">Describes a package added event.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="b3989-104">Siehe <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" />, <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" /> und <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" />.</span><span class="sxs-lookup"><span data-stu-id="b3989-104">See <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" />, <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" />, and <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageAddedEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageAddedEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b3989-105">Erstellt eine neue Instanz der <see cref="T:System.Fabric.PackageAddedEventArgs`1" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b3989-105">Creates a new instance of the <see cref="T:System.Fabric.PackageAddedEventArgs`1" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Package">
      <MemberSignature Language="C#" Value="public TPackage Package { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage Package" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageAddedEventArgs`1.Package" />
      <MemberSignature Language="VB.NET" Value="Public Property Package As TPackage" />
      <MemberSignature Language="F#" Value="member this.Package : 'Package with get, set" Usage="System.Fabric.PackageAddedEventArgs&lt;'Package (requires 'Package : null)&gt;.Package" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TPackage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b3989-106">Ruft ab oder legt den Code, der Daten oder der Konfiguration Paket, das das Dienstmanifest hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b3989-106">Gets or sets the code, data, or configuration package that was added to the Service Manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b3989-107">Der Code, der Daten oder Konfiguration Paket, das das Dienstmanifest hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b3989-107">The code, data, or configuration package that was added to the Service Manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>