<Type Name="ServiceReplicaStatus" FullName="System.Fabric.Query.ServiceReplicaStatus">
  <TypeSignature Language="C#" Value="public enum ServiceReplicaStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceReplicaStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceReplicaStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceReplicaStatus" />
  <TypeSignature Language="F#" Value="type ServiceReplicaStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Status des Replikats.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Down">
      <MemberSignature Language="C#" Value="Down" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Down = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberSignature Language="VB.NET" Value="Down" />
      <MemberSignature Language="F#" Value="Down = 4" Usage="System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Replikat ist nicht aktiv.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Dropped">
      <MemberSignature Language="C#" Value="Dropped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Dropped = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberSignature Language="VB.NET" Value="Dropped" />
      <MemberSignature Language="F#" Value="Dropped = 5" Usage="System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>Replikat wird gelöscht. Dies bedeutet, dass das Replikat aus der Replikatgruppe entfernt wurde. Wenn es beibehalten wird, wurde seinen Status gelöscht.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InBuild">
      <MemberSignature Language="C#" Value="InBuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus InBuild = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberSignature Language="VB.NET" Value="InBuild" />
      <MemberSignature Language="F#" Value="InBuild = 1" Usage="System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Replikat wird erstellt. Dies bedeutet, dass ein primäres Replikat auf dieses Replikat seeding ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Ungültig</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Ready = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 3" Usage="System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Replikat ist bereit.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Standby">
      <MemberSignature Language="C#" Value="Standby" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Standby = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberSignature Language="VB.NET" Value="Standby" />
      <MemberSignature Language="F#" Value="Standby = 2" Usage="System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            Das Replikat neu gestartet wurde, und wird als Reservesystem arbeitet gehalten.
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>