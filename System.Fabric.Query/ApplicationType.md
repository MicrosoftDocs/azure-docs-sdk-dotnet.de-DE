<Type Name="ApplicationType" FullName="System.Fabric.Query.ApplicationType">
  <TypeSignature Language="C#" Value="public sealed class ApplicationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationType" />
  <TypeSignature Language="F#" Value="type ApplicationType = class" />
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
      <para>Stellt einen Anwendungstyp dar.</para>
    </summary>
    <remarks>
      <para>
                    Ein Anwendungstyp ist eine Kategorisierung einer Anwendung und besteht aus einem Bündel von Diensttypen.
                    Details finden Sie in diesem <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">Dokument</see>.
                </para>
      <para>
                    Anwendungstyp enthält alle, die für eine funktionierende Anwendung, z. B. der Codepakete für die Dienste erforderlich ist, die sie umfasst. Außerdem enthält es ein Anwendungsmanifest. Wenn eine Anwendung aus einer Anwendung vom Typ instanziiert wird, kann das Anwendungsmanifest, das mit der Anwendung verknüpft sind, überschrieben werden. Der Anwendungstyp muss hochgeladen werden, bevor eine Anwendung erstellt werden kann.
                    </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeDefinitionKind As ApplicationTypeDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKind : System.Fabric.Query.ApplicationTypeDefinitionKind" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die definitionsart.</para>
        </summary>
        <value>
          <para>Der definitionsart enthält einen der Werte in der Enumeration definierten <see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />.</para>
          <para>Gibt den Mechanismus der Benutzer Benutzer um einen Anwendungstyp Service Fabric zu definieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeName" />
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
          <para>Der Name des Anwendungstyps die im Manifest Anwendung definiert ist. Dieser Wert in Verbindung mit die Version der Anwendung erstellen einen eindeutigen Bezeichner für den Anwendungstyp.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
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
          <para>Ruft die Version der Anwendung ab.</para>
        </summary>
        <value>
          <para>Die anwendungstypversion, die im Manifest Anwendung definiert ist. Dieser Wert in Verbindung mit der Name des Anwendungstyps erstellen einen eindeutigen Bezeichner für den Anwendungstyp. Dieser Wert muss nicht numerischen Wert sein.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList DefaultParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList DefaultParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.DefaultParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.ApplicationType.DefaultParameters" />
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
          <para>Ruft die Parameter der Anwendung ab.</para>
        </summary>
        <value>
          <para>Die Anwendung-Standardparameter, im Manifest Anwendung definiert. Wenn eine Anwendung aus diesen Anwendungstyp instanziiert wird, sind diese Parameter verwendet, es sei denn, sie außer Kraft gesetzt werden. Die instanziierte Anwendung möglicherweise auch weitere Anwendungsparameter definiert, zusätzlich zu den in dieser Eigenschaft definiert.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ApplicationTypeStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Query.ApplicationTypeStatus" Usage="System.Fabric.Query.ApplicationType.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Status der Anwendung-Typ ab.</para>
        </summary>
        <value>
          <para>Enthält einen der Werte in der Enumeration definierten Typ Anwendungsstatus <see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.ApplicationType.StatusDetails" />
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
          <para>Ruft den Anwendungstyp Statusdetails an.</para>
        </summary>
        <value>
          <para>Die Anwendung Typ Statusdetails. Dieses Objekt enthält Informationen zu diesen Anwendungstyp Bereitstellung.
            Während der Bereitstellung enthält diese Statusinformationen zu erhalten. Bereitstellung sollte nicht ausgeführt werden, dadurch wird die Fehlermeldung angezeigt.
            Andernfalls wird dieses Feld leer gelassen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>