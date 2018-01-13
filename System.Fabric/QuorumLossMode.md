<Type Name="QuorumLossMode" FullName="System.Fabric.QuorumLossMode">
  <TypeSignature Language="C#" Value="public enum QuorumLossMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed QuorumLossMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.QuorumLossMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum QuorumLossMode" />
  <TypeSignature Language="F#" Value="type QuorumLossMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Typ des QuorumLoss, die aufgerufen wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllReplicas">
      <MemberSignature Language="C#" Value="AllReplicas" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode AllReplicas = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.AllReplicas" />
      <MemberSignature Language="VB.NET" Value="AllReplicas" />
      <MemberSignature Language="F#" Value="AllReplicas = 2" Usage="System.Fabric.QuorumLossMode.AllReplicas" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>Vollständige quorummodus Verlust: alle Replikate für eine Partition, die ausgeschaltet wird, führt dies eine Quorum dienstunterbrechung. </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.QuorumLossMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Reserviert.  Übergeben Sie diesen Wert nicht an die API.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="QuorumReplicas">
      <MemberSignature Language="C#" Value="QuorumReplicas" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.QuorumLossMode QuorumReplicas = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.QuorumLossMode.QuorumReplicas" />
      <MemberSignature Language="VB.NET" Value="QuorumReplicas" />
      <MemberSignature Language="F#" Value="QuorumReplicas = 1" Usage="System.Fabric.QuorumLossMode.QuorumReplicas" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.QuorumLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Partielle quorummodus Verlust: minimale Anzahl von Replikaten für eine Partition, die ausgeschaltet wird, führt dies eine Quorum dienstunterbrechung.</summary>
      </Docs>
    </Member>
  </Members>
</Type>