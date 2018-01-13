<Type Name="DataPackage" FullName="System.Fabric.DataPackage">
  <TypeSignature Language="C#" Value="public sealed class DataPackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataPackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataPackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataPackage" />
  <TypeSignature Language="F#" Value="type DataPackage = class" />
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
      <para>Diese Klasse stellt ein Datenpaket in der Anwendung. Ein Datenpaket besteht aus statischen Daten (die ein Upgrade ausgeführt werden können), die von der Anwendung verarbeitet wird. Weitere Informationen finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.DataPackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.DataPackageDescription" Usage="System.Fabric.DataPackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.Description.PackageDescription" /> zugeordnete Objekt der <see cref="T:System.Fabric.DataPackage" />. Die paketbeschreibung kann verwendet werden, Zugriff auf zusätzliche Informationen über dieses Paket wie den Namen, Version usw. </para>
        </summary>
        <value>
          <para>Das <see cref="T:System.Fabric.Description.PackageDescription" /> zugeordnete <see cref="T:System.Fabric.DataPackage" />-Objekt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.DataPackage.Path" />
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
          <para>Ruft den lokalen Pfad der <see cref="T:System.Fabric.DataPackage" />. Dieser Pfad enthält den Inhalt des Datenpakets.</para>
        </summary>
        <value>
          <para>Der lokale Pfad der <see cref="T:System.Fabric.DataPackage" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>