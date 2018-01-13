<Type Name="ServiceInitializationParameters" FullName="System.Fabric.ServiceInitializationParameters">
  <TypeSignature Language="C#" Value="public abstract class ServiceInitializationParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceInitializationParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceInitializationParameters" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceInitializationParameters" />
  <TypeSignature Language="F#" Value="type ServiceInitializationParameters = class" />
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
      <para>Stellt die Basisklasse für Service-Initialisierungsparameter, die übergeben werden, die <see cref="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" /> -Methode eines Diensts.</para>
    </summary>
    <remarks>
      <para>Abgeleitete Typen definieren die Initialisierungsdaten, die spezifisch für Zustandslose und zustandsbehaftete Dienste sind.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageActivationContext">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackageActivationContext CodePackageActivationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.CodePackageActivationContext CodePackageActivationContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.CodePackageActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageActivationContext As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="member this.CodePackageActivationContext : System.Fabric.CodePackageActivationContext" Usage="System.Fabric.ServiceInitializationParameters.CodePackageActivationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Aktivierungskontext, der das Codepaket zugeordnet ist, die den Dienst enthält.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.CodePackageActivationContext" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.ServiceInitializationParameters.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt die angepasste Initialisierung von Daten, die als Teil der Ersteller des Diensts bereitgestellt wird die <see cref="T:System.Fabric.Description.ServiceDescription" /> Klasse.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Byte" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceInitializationParameters.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den eindeutigen Bezeichner der Dienstpartition an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Guid" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceInitializationParameters.ServiceName" />
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
          <para>Gibt die Service Fabric-Namen des Diensts an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Uri" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.ServiceInitializationParameters.ServiceTypeName" />
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
          <para>Gibt den Namen des Typs des Diensts an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>