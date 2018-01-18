<Type Name="PackageModifiedEventArgs&lt;TPackage&gt;" FullName="System.Fabric.PackageModifiedEventArgs&lt;TPackage&gt;">
  <TypeSignature Language="C#" Value="public sealed class PackageModifiedEventArgs&lt;TPackage&gt; : EventArgs where TPackage : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PackageModifiedEventArgs`1&lt;class TPackage&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageModifiedEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PackageModifiedEventArgs(Of TPackage)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt; = class&#xA;    inherit EventArgs" />
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
              <span data-ttu-id="a1938-101">Der Typ des geänderten Pakets.</span><span class="sxs-lookup"><span data-stu-id="a1938-101">The type of the modified package.</span></span>
            </typeparam>
    <summary>
              <span data-ttu-id="a1938-102">Stellt die Ereignisargumente für das Paket Änderung dar.</span><span class="sxs-lookup"><span data-stu-id="a1938-102">Represents the event arguments for package modification.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageModifiedEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageModifiedEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
              <span data-ttu-id="a1938-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.PackageModifiedEventArgs`1" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a1938-103">Initializes a new instance of the <see cref="T:System.Fabric.PackageModifiedEventArgs`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewPackage">
      <MemberSignature Language="C#" Value="public TPackage NewPackage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage NewPackage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageModifiedEventArgs`1.NewPackage" />
      <MemberSignature Language="VB.NET" Value="Public Property NewPackage As TPackage" />
      <MemberSignature Language="F#" Value="member this.NewPackage : 'Package with get, set" Usage="System.Fabric.PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt;.NewPackage" />
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
              <span data-ttu-id="a1938-104">Ruft ab oder legt das neue Paket.</span><span class="sxs-lookup"><span data-stu-id="a1938-104">Gets or sets the new package.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="a1938-105">Das neue Paket, das die alte Paket ersetzt.</span><span class="sxs-lookup"><span data-stu-id="a1938-105">The new package that replaces the old package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OldPackage">
      <MemberSignature Language="C#" Value="public TPackage OldPackage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage OldPackage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageModifiedEventArgs`1.OldPackage" />
      <MemberSignature Language="VB.NET" Value="Public Property OldPackage As TPackage" />
      <MemberSignature Language="F#" Value="member this.OldPackage : 'Package with get, set" Usage="System.Fabric.PackageModifiedEventArgs&lt;'Package (requires 'Package : null)&gt;.OldPackage" />
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
              <span data-ttu-id="a1938-106">Abrufen oder Festlegen des alten Pakets durch, die geändert werden.</span><span class="sxs-lookup"><span data-stu-id="a1938-106">Gets or sets the old package that is modified.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="a1938-107">Die alte Paket, die geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a1938-107">The old package that is modified.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>