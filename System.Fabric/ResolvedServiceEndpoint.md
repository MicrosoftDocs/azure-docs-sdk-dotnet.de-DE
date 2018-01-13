<Type Name="ResolvedServiceEndpoint" FullName="System.Fabric.ResolvedServiceEndpoint">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServiceEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServiceEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServiceEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServiceEndpoint" />
  <TypeSignature Language="F#" Value="type ResolvedServiceEndpoint = class" />
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
      <para>Stellt einen aufgelösten Dienstendpunkt enthält Informationen zu der Rolle "Replikat" Partition und die Adresse, der er überwacht.</para>
    </summary>
    <remarks>
      <para>
            Die aufgelöste Dienst-Endpunkte zurückgegeben werden, von <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />, im Rahmen des <see cref="T:System.Fabric.ResolvedServicePartition" />.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.ResolvedServiceEndpoint.Address" />
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
          <para>Ruft die Adresse für den Endpunkt ab.
            Die dienstreplikats ermöglicht diese Zeichenfolge auf Service Fabric, damit Benutzer wissen, wo es erreicht werden kann.</para>
        </summary>
        <value>
          <para>Die Adresse für den Endpunkt, in denen die dienstreplikats oder einer Instanz erreicht werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServiceEndpointRole Role" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ServiceEndpointRole" />
      <MemberSignature Language="F#" Value="member this.Role : System.Fabric.ServiceEndpointRole" Usage="System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Rolle eines Dienstendpunkts ab.</para>
        </summary>
        <value>
          <para>Die Rolle eines Dienstendpunkts.</para>
        </value>
        <remarks>
          <para>Die <see cref="T:System.Fabric.ServiceEndpointRole" /> wird von einem Client verwendet, um zu bestimmen, welche Dienstinstanz oder auswählen und Herstellen einer Verbindung mit Replikat.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>