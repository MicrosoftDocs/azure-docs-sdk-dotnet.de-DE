<Type Name="SubtaskState" FullName="Microsoft.Azure.Batch.Protocol.Models.SubtaskState">
  <TypeSignature Language="C#" Value="public enum SubtaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SubtaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.SubtaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum SubtaskState" />
  <TypeSignature Language="F#" Value="type SubtaskState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert Werte für SubtaskState an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState Completed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Task ist nicht mehr berechtigt, in der Regel ausführen, da die Aufgabe erfolgreich ausgeführt wurde, oder der Task nicht erfolgreich abgeschlossen wurde, und Wiederholungslimit erreicht wurde. Eine Aufgabe wird ebenfalls markiert, als abgeschlossen, wenn ein Fehler aufgetreten ist, starten den Vorgang, oder wenn die Aufgabe beendet wurde.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState Preparing = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="preparing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Task auf einen Serverknoten zugewiesen wurde, aber wartet darauf, dass ein erforderlicher Schritt der Auftrag zur Vorbereitung für den Knoten ausführen. Wenn der Auftrag zur Vorbereitung Task erfolgreich ausgeführt wird, wird der Vorgang wird für die Ausführung verschoben. Wenn der Auftrag zur Vorbereitung Task fehlschlägt, wird die Aufgabe aktiv zurück und sind berechtigt, die auf einen anderen Knoten zugewiesen werden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Task wird auf einem Serverknoten ausgeführt. Dies umfasst die Vorbereitung auf Aufgabenebene, z. B. Ressourcendateien herunterladen oder Bereitstellen von Anwendungspaketen für den Task angegeben – es bedeutet nicht unbedingt, dass die Befehlszeile der Aufgabe mit der Ausführung begonnen hat.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>