<Type Name="Application" FullName="System.Fabric.Query.Application">
  <TypeSignature Language="C#" Value="public sealed class Application" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Application extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Application" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Application" />
  <TypeSignature Language="F#" Value="type Application = class" />
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
      <para>Beschreibt eine Anwendungsinstanz, die durch Anwendungsname,-Diagramm nach der Anwendung, Anwendungsparameter Integritätsstatus usw. gekennzeichnet ist.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationDefinitionKind ApplicationDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationDefinitionKind ApplicationDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationDefinitionKind As ApplicationDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationDefinitionKind : System.Fabric.Query.ApplicationDefinitionKind" Usage="System.Fabric.Query.Application.ApplicationDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die definitionsart.</para>
        </summary>
        <value>
          <para>Der definitionsart enthält einen der Werte in der Enumeration definierten <see cref="P:System.Fabric.Query.Application.ApplicationDefinitionKind" />.</para>
          <para>Gibt den Mechanismus der Benutzer verwendet, um eine Service Fabric-Anwendung zu definieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Query.Application.ApplicationName" />
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
          <para>Ruft den Namen der Anwendung als einen URI ab.</para>
        </summary>
        <value>
          <para>Der Namen der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.Application.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Parameter der Anwendung, das eine Auflistung von Schlüssel und entsprechenden Werten ab.</para>
        </summary>
        <value>
          <para>Die Parameter der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationStatus ApplicationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationStatus ApplicationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationStatus As ApplicationStatus" />
      <MemberSignature Language="F#" Value="member this.ApplicationStatus : System.Fabric.Query.ApplicationStatus" Usage="System.Fabric.Query.Application.ApplicationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Status der Anwendung als <see cref="T:System.Fabric.Query.ApplicationStatus" />.</para>
        </summary>
        <value>
          <para>Der Status der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.Application.ApplicationTypeName" />
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
          <para>Ruft ab, der Name des Anwendungstyps entsprechend den Angaben im Anwendungsmanifest.</para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.Application.ApplicationTypeVersion" />
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
          <para>Ruft die anwendungstypversion entsprechend den Angaben im Anwendungsmanifest.</para>
        </summary>
        <value>
          <para>Die Anwendungstypversion.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Application.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den aggregierten Zustand der Anwendung als <see cref="T:System.Fabric.Health.HealthState" />. </para>
        </summary>
        <value>
          <para>Der zusammengefassten Integrität der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList UpgradeParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList UpgradeParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.UpgradeParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.UpgradeParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.Application.UpgradeParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ApplicationUpgradeProgress.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Als veraltet markiert: Darf nicht verwendet werden. Finden Sie unter <see cref="T:System.Fabric.ApplicationUpgradeProgress" /> stattdessen.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.Description.ApplicationParameterList" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTypeVersion">
      <MemberSignature Language="C#" Value="public string UpgradeTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.UpgradeTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeTypeVersion : string" Usage="System.Fabric.Query.Application.UpgradeTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ApplicationUpgradeProgress.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Als veraltet markiert: Darf nicht verwendet werden. Finden Sie unter <see cref="T:System.Fabric.ApplicationUpgradeProgress" /> stattdessen.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>