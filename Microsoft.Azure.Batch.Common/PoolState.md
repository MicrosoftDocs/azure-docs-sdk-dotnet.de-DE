<Type Name="PoolState" FullName="Microsoft.Azure.Batch.Common.PoolState">
  <TypeSignature Language="C#" Value="public enum PoolState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PoolState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.PoolState" />
  <TypeSignature Language="VB.NET" Value="Public Enum PoolState" />
  <TypeSignature Language="F#" Value="type PoolState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Der Status eines Pools.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.PoolState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Pool ist zum Ausführen von Aufgaben nach der Verfügbarkeit von Serverknoten verfügbar.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Deleting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 1" Usage="Microsoft.Azure.Batch.Common.PoolState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Benutzer hat angefordert, dass der Pool gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Upgrading = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 2" Usage="Microsoft.Azure.Batch.Common.PoolState.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Benutzer hat angefordert, dass das Betriebssystem der Knoten für den Pool aktualisiert werden, aber der Upgradevorgang noch nicht abgeschlossen (d. h. einige Knoten im Pool wurden noch nicht aktualisiert).
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>