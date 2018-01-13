<Type Name="ChaosStatus" FullName="System.Fabric.Chaos.DataStructures.ChaosStatus">
  <TypeSignature Language="C#" Value="public enum ChaosStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ChaosStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ChaosStatus" />
  <TypeSignature Language="F#" Value="type ChaosStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Stellt die Aufgabe, die Chaos gegenwärtig ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Chaos.DataStructures.ChaosStatus None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Chaos.DataStructures.ChaosStatus.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.Chaos.DataStructures.ChaosStatus.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der aktuelle Vorgang ungültig ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Chaos.DataStructures.ChaosStatus Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Chaos.DataStructures.ChaosStatus.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="System.Fabric.Chaos.DataStructures.ChaosStatus.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass Chaos Aktionen im Rahmen des Fehlers ratenbasierte ausgeführt wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopped">
      <MemberSignature Language="C#" Value="Stopped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Chaos.DataStructures.ChaosStatus Stopped = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Chaos.DataStructures.ChaosStatus.Stopped" />
      <MemberSignature Language="VB.NET" Value="Stopped" />
      <MemberSignature Language="F#" Value="Stopped = 2" Usage="System.Fabric.Chaos.DataStructures.ChaosStatus.Stopped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Chaos.DataStructures.ChaosStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass Chaos die ratenbasierte Fehler abgeschlossen wurde, und jetzt überprüft wird, wenn der Cluster stabil und fehlerfrei ist.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>