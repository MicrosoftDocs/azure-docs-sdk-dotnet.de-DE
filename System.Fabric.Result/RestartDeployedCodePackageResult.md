<Type Name="RestartDeployedCodePackageResult" FullName="System.Fabric.Result.RestartDeployedCodePackageResult">
  <TypeSignature Language="C#" Value="public class RestartDeployedCodePackageResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RestartDeployedCodePackageResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartDeployedCodePackageResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartDeployedCodePackageResult" />
  <TypeSignature Language="F#" Value="type RestartDeployedCodePackageResult = class" />
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
            Gibt zurück, Neustart Code Ergebnis Paketobjekts bereitgestellt. 
            </summary>
    <remarks>
            Diese Klasse gibt die "nodename", Parameter "ApplicationName", ServiceManifestName, CodePackageName, CodePackageInstanceId und SelectedReplica-Informationen für das der bereitgestellten Code Paketaktion aufgerufen wurde. ReplicaSelector werden keine für den Fall, dass Anwendung Selecetd mit Nodename, Anwendungsname, Dienstmanifest, codepaketname und Code Paket Instanz-Id ist.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ApplicationName" />
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
            Ruft die Namen der Anwendung ab.
            </summary>
        <value>Der Anwendungsname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageInstanceId">
      <MemberSignature Language="C#" Value="public long CodePackageInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CodePackageInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.CodePackageInstanceId : int64" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Code-Paket-Instanz-Id ab.
            </summary>
        <value>Die Code-Paket-Id, als einen Long-Wert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.CodePackageName" />
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
            Ruft die codepaketname ab.
            </summary>
        <value>Der Paketname für den Code.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.NodeName" />
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
            Ruft Name des Knotens ab.
            </summary>
        <value>Der Knotenname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedReplica SelectedReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedReplica SelectedReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedReplica As SelectedReplica" />
      <MemberSignature Language="F#" Value="member this.SelectedReplica : System.Fabric.SelectedReplica" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.SelectedReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den ausgewählten Replikat.
            </summary>
        <value>Das SelectedReplica-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServiceManifestName" />
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
            Ruft die dienstmanifestname ab.
            </summary>
        <value>Der dienstmanifestname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" />
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
            Ruft die ActivationId des Dienstpakets ab.
            </summary>
        <value>
          <para>
            Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt. Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn nicht angegeben ist, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Result.RestartDeployedCodePackageResult.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartDeployedCodePackageResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartDeployedCodePackageResult.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Formatiert die Daten in RestartDeployedCodePackageResult als Zeichenfolge.
            </summary>
        <returns>Die formatierte Zeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>