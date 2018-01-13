<Type Name="ComposeDeploymentStatusQueryDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die abfrageeingabe von System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) verwendet.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentStatusQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Instanziiert eine Instanz des <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </value>
        <remarks>
          <para>ContinuationToken wird von einer vorherigen Abfrage empfangen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentNameFilter">
      <MemberSignature Language="C#" Value="public string DeploymentNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentNameFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentNameFilter : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt der Namen der Bereitstellung, bei der Abfrage bilden.</para>
        </summary>
        <value>
          <para>Der Name des bilden Bereitstellung bei der Abfrage.</para>
        </value>
        <remarks>
          <para> Wenn DeploymentNameFilter nicht angegeben wird, bilden alle Bereitstellungen zurückgegeben werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems, die pro Seite zurückgegeben werden können.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Wenn dieser Wert nicht festgelegt ist, wird es nicht verwendet, um die Anzahl der zurückgegebenen Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems zu beschränken.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>