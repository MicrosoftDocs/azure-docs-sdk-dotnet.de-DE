<Type Name="ServiceCorrelationScheme" FullName="System.Fabric.Description.ServiceCorrelationScheme">
  <TypeSignature Language="C#" Value="public enum ServiceCorrelationScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceCorrelationScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceCorrelationScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceCorrelationScheme" />
  <TypeSignature Language="F#" Value="type ServiceCorrelationScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt an, dass dieser Dienst mit einem anderen Dienst zugeordnet ist, und die Beziehung mit diesem Dienst beschreibt.</para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Affinity">
      <MemberSignature Language="C#" Value="Affinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Affinity = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberSignature Language="VB.NET" Value="Affinity" />
      <MemberSignature Language="F#" Value="Affinity = 1" Usage="System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass dieser Dienst eine Affinität mit einem anderen Dienst verfügt. Für die Abwärtskompatibilität zur Verfügung gestellt, sollten Sie die Optionen ausgerichtet oder NonAlignedAffinity ausgehandelt.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="AlignedAffinity">
      <MemberSignature Language="C#" Value="AlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme AlignedAffinity = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="AlignedAffinity" />
      <MemberSignature Language="F#" Value="AlignedAffinity = 2" Usage="System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Angeglichene Affinität wird sichergestellt, dass der primäre Partitionen der kategorisierten Dienste auf demselben Knoten angeordnet sind. Dies ist die Standardeinstellung und ist identisch mit das Schema "Affinität" auswählen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Ein Schema ungültige Korrelation. kann nicht verwendet werden.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAlignedAffinity">
      <MemberSignature Language="C#" Value="NonAlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme NonAlignedAffinity = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="NonAlignedAffinity" />
      <MemberSignature Language="F#" Value="NonAlignedAffinity = 3" Usage="System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Nicht angeglichene Affinität wird sichergestellt, dass alle Replikate der einzelnen Dienste auf demselben Knoten platziert werden. Im Gegensatz zu Affinität ausgerichtet kann dies nicht garantiert, dass die Replikate der bestimmten Rolle zusammengestellt werden. </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>