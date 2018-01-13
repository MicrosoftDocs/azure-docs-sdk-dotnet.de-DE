<Type Name="CodePackage" FullName="System.Fabric.CodePackage">
  <TypeSignature Language="C#" Value="public sealed class CodePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CodePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CodePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CodePackage" />
  <TypeSignature Language="F#" Value="type CodePackage = class" />
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
      <para>Stellt die Paketdefinition Code dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.CodePackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.CodePackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As CodePackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.CodePackageDescription" Usage="System.Fabric.CodePackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.CodePackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="T:System.Fabric.Description.CodePackageDescription" /> für den <see cref="T:System.Fabric.CodePackage" /> ab.</para>
        </summary>
        <value>
          <para>Der <see cref="T:System.Fabric.Description.CodePackageDescription" /> für den <see cref="T:System.Fabric.CodePackage" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryPointRunAsPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.RunAsPolicyDescription EntryPointRunAsPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.RunAsPolicyDescription EntryPointRunAsPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.EntryPointRunAsPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryPointRunAsPolicy As RunAsPolicyDescription" />
      <MemberSignature Language="F#" Value="member this.EntryPointRunAsPolicy : System.Fabric.Description.RunAsPolicyDescription" Usage="System.Fabric.CodePackage.EntryPointRunAsPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.RunAsPolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> zugeordneten Main-Einstiegspunkt in die <see cref="T:System.Fabric.CodePackage" />.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> zugeordneten Main-Einstiegspunkt in die <see cref="T:System.Fabric.CodePackage" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.CodePackage.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Pfad zu der <see cref="T:System.Fabric.CodePackage" />.</para>
        </summary>
        <value>
          <para>Der Pfad zu der <see cref="T:System.Fabric.CodePackage" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupEntryPointRunAsPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.RunAsPolicyDescription SetupEntryPointRunAsPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.RunAsPolicyDescription SetupEntryPointRunAsPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackage.SetupEntryPointRunAsPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SetupEntryPointRunAsPolicy As RunAsPolicyDescription" />
      <MemberSignature Language="F#" Value="member this.SetupEntryPointRunAsPolicy : System.Fabric.Description.RunAsPolicyDescription" Usage="System.Fabric.CodePackage.SetupEntryPointRunAsPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.RunAsPolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> mit Setup EntryPoint in <see cref="T:System.Fabric.CodePackage" />.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Description.RunAsPolicyDescription" /> mit Setup EntryPoint in <see cref="T:System.Fabric.CodePackage" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>