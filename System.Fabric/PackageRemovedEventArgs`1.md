<Type Name="PackageRemovedEventArgs&lt;TPackage&gt;" FullName="System.Fabric.PackageRemovedEventArgs&lt;TPackage&gt;">
  <TypeSignature Language="C#" Value="public sealed class PackageRemovedEventArgs&lt;TPackage&gt; : EventArgs where TPackage : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PackageRemovedEventArgs`1&lt;class TPackage&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageRemovedEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PackageRemovedEventArgs(Of TPackage)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type PackageRemovedEventArgs&lt;'Package (requires 'Package : null)&gt; = class&#xA;    inherit EventArgs" />
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
      <para>Der Typ des Pakets beschrieben wird. Finden Sie unter <see cref="T:System.Fabric.CodePackage" />, <see cref="T:System.Fabric.ConfigurationPackage" />, <see cref="T:System.Fabric.DataPackage" />.</para>
    </typeparam>
    <summary>
      <para>Beschreibt ein Ereignis des Pakets entfernt. </para>
    </summary>
    <remarks>
      <para>Siehe <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" />, <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" /> und <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageRemovedEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageRemovedEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.PackageRemovedEventArgs`1" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Package">
      <MemberSignature Language="C#" Value="public TPackage Package { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TPackage Package" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageRemovedEventArgs`1.Package" />
      <MemberSignature Language="VB.NET" Value="Public Property Package As TPackage" />
      <MemberSignature Language="F#" Value="member this.Package : 'Package with get, set" Usage="System.Fabric.PackageRemovedEventArgs&lt;'Package (requires 'Package : null)&gt;.Package" />
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
          <para>Ruft ab oder legt den Code, der Konfiguration oder Daten Paket, das aus der Dienstmanifest entfernt wurde.</para>
        </summary>
        <value>
          <para>Der Code, der Konfiguration oder Daten Paket, das aus der Dienstmanifest entfernt wurde.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>