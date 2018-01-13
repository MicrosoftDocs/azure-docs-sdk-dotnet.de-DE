<Type Name="HostIsolationMode" FullName="System.Fabric.HostIsolationMode">
  <TypeSignature Language="C#" Value="public enum HostIsolationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed HostIsolationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.HostIsolationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum HostIsolationMode" />
  <TypeSignature Language="F#" Value="type HostIsolationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Gibt an, wird der Isolationsmodus des Haupteinstiegspunkt eines Pakets Code bei Hosttyp <see cref="F:System.Fabric.HostType.ContainerHost" />. Dies wird im Rahmen der Container-Host-Richtlinien im Anwendungsmanifest angegeben, beim Dienstmanifest importieren.
            </para>
      <remarks>
            Geben Sie für Host außer <see cref="F:System.Fabric.HostType.ContainerHost" />, ihr Wert ist <see cref="F:System.Fabric.HostIsolationMode.None" />.
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HyperV">
      <MemberSignature Language="C#" Value="HyperV" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode HyperV = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.HyperV" />
      <MemberSignature Language="VB.NET" Value="HyperV" />
      <MemberSignature Language="F#" Value="HyperV = 2" Usage="System.Fabric.HostIsolationMode.HyperV" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            Gibt an, die <see cref="F:System.Fabric.HostType.ContainerHost" /> ist ein Hyper-V-Container.
            Dies gilt für nur Windows-Containern.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.HostIsolationMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, Isolationsmodus gilt nicht für den angegebenen <see cref="T:System.Fabric.HostType" />.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="Process" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode Process = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.Process" />
      <MemberSignature Language="VB.NET" Value="Process" />
      <MemberSignature Language="F#" Value="Process = 1" Usage="System.Fabric.HostIsolationMode.Process" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Der Standardmodus für die Isolation für eine <see cref="F:System.Fabric.HostType.ContainerHost" />.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>