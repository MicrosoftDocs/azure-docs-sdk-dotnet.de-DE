<Type Name="DeployedApplication" FullName="System.Fabric.Query.DeployedApplication">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplication extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplication" />
  <TypeSignature Language="F#" Value="type DeployedApplication = class" />
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
      <para>Beschreibt eine Instanz einer Anwendung Dienst-Hosts auf einem Service Fabric-Knoten ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Query.DeployedApplication.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Anwendung ab.</para>
        </summary>
        <value>
          <para>Der Anwendungsname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.DeployedApplication.ApplicationTypeName" />
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
          <para>Ruft den Typnamen der Anwendung ab.</para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedApplicationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedApplicationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.DeployedApplicationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedApplication.DeployedApplicationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Status der bereitgestellten Anwendungsinstanz ab.</para>
        </summary>
        <value>
          <para>Der Status der bereitgestellten Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.Query.DeployedApplication.LogDirectory" />
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
          <para>Ruft ab, der protokollverzeichnispfad, die von der bereitgestellten Anwendung-Instanz verwendet.</para>
        </summary>
        <value>
          <para>Der Verzeichnispfad für die Protokolldatei von der bereitgestellten Anwendung-Instanz verwendet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.Query.DeployedApplication.TempDirectory" />
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
          <para>Ruft den Pfad des temporären Verzeichnisses verwendet werden, von der bereitgestellten Anwendung-Instanz ab.</para>
        </summary>
        <value>
          <para>Der Pfad des temporären Verzeichnisses von der bereitgestellten Anwendung-Instanz verwendet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.Query.DeployedApplication.WorkDirectory" />
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
          <para>Ruft die Arbeit Verzeichnispfad verwendet, die von der bereitgestellten Anwendung-Instanz ab.</para>
        </summary>
        <value>
          <para>Der Verzeichnispfad für die Arbeit von der bereitgestellten Anwendung-Instanz verwendet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>