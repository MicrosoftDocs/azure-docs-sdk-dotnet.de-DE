<Type Name="OperationType" FullName="System.Fabric.OperationType">
  <TypeSignature Language="C#" Value="public enum OperationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OperationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.OperationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum OperationType" />
  <TypeSignature Language="F#" Value="type OperationType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Typ des Vorgangs, der über den Stream Kopie oder Replikation empfangen wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AtomicGroupOperation">
      <MemberSignature Language="C#" Value="AtomicGroupOperation" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType AtomicGroupOperation = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.AtomicGroupOperation" />
      <MemberSignature Language="VB.NET" Value="AtomicGroupOperation" />
      <MemberSignature Language="F#" Value="AtomicGroupOperation = 32" Usage="System.Fabric.OperationType.AtomicGroupOperation" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Vorgang eine atomare Gruppe angehört.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="CommitAtomicGroup">
      <MemberSignature Language="C#" Value="CommitAtomicGroup" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType CommitAtomicGroup = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.CommitAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="CommitAtomicGroup" />
      <MemberSignature Language="F#" Value="CommitAtomicGroup = 64" Usage="System.Fabric.OperationType.CommitAtomicGroup" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine bestimmte unteilbare Gruppe übernommen wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="CreateAtomicGroup">
      <MemberSignature Language="C#" Value="CreateAtomicGroup" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType CreateAtomicGroup = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.CreateAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="CreateAtomicGroup" />
      <MemberSignature Language="F#" Value="CreateAtomicGroup = 16" Usage="System.Fabric.OperationType.CreateAtomicGroup" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine bestimmte unteilbare Gruppe erstellt werden soll.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EndOfStream">
      <MemberSignature Language="C#" Value="EndOfStream" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType EndOfStream = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.EndOfStream" />
      <MemberSignature Language="VB.NET" Value="EndOfStream" />
      <MemberSignature Language="F#" Value="EndOfStream = 2" Usage="System.Fabric.OperationType.EndOfStream" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</summary>
      </Docs>
    </Member>
    <Member MemberName="HasAtomicGroupMask">
      <MemberSignature Language="C#" Value="HasAtomicGroupMask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType HasAtomicGroupMask = int32(240)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.HasAtomicGroupMask" />
      <MemberSignature Language="VB.NET" Value="HasAtomicGroupMask" />
      <MemberSignature Language="F#" Value="HasAtomicGroupMask = 240" Usage="System.Fabric.OperationType.HasAtomicGroupMask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>240</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Vorgang eine atomare Gruppe Maske.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.OperationType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Vorgang ungültig ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Normal">
      <MemberSignature Language="C#" Value="Normal" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType Normal = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.Normal" />
      <MemberSignature Language="VB.NET" Value="Normal" />
      <MemberSignature Language="F#" Value="Normal = 1" Usage="System.Fabric.OperationType.Normal" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Vorgang nicht Teil einer atomare Gruppe ist und als eigenständigen Kopie oder Replikation Vorgang verarbeitet werden soll.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollbackAtomicGroup">
      <MemberSignature Language="C#" Value="RollbackAtomicGroup" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.OperationType RollbackAtomicGroup = int32(128)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.OperationType.RollbackAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="RollbackAtomicGroup" />
      <MemberSignature Language="F#" Value="RollbackAtomicGroup = 128" Usage="System.Fabric.OperationType.RollbackAtomicGroup" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <MemberValue>128</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine bestimmte unteilbare Gruppe ein Rollback ausgeführt werden soll.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>