<Type Name="GraphStatusCode" FullName="Microsoft.Azure.Graphs.GraphStatusCode">
  <TypeSignature Language="C#" Value="public enum GraphStatusCode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed GraphStatusCode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphStatusCode" />
  <TypeSignature Language="VB.NET" Value="Public Enum GraphStatusCode" />
  <TypeSignature Language="F#" Value="type GraphStatusCode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Fehlercodes, die Ausnahmen, die von der Graph-Bibliothek zugeordnet werden.
            RFC: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="Authenticate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Authenticate = int32(407)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Authenticate" />
      <MemberSignature Language="VB.NET" Value="Authenticate" />
      <MemberSignature Language="F#" Value="Authenticate = 407" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Authenticate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>407</MemberValue>
      <Docs>
        <summary>
            Eine Herausforderung vom Server für den Client zum Authentifizieren der Anforderung.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidRequestArguments">
      <MemberSignature Language="C#" Value="InvalidRequestArguments" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode InvalidRequestArguments = int32(499)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.InvalidRequestArguments" />
      <MemberSignature Language="VB.NET" Value="InvalidRequestArguments" />
      <MemberSignature Language="F#" Value="InvalidRequestArguments = 499" Usage="Microsoft.Azure.Graphs.GraphStatusCode.InvalidRequestArguments" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>499</MemberValue>
      <Docs>
        <summary>
            Die Anforderungsnachricht wurde analysiert, aber die Argumente in der Nachricht wurden in Konflikt stehende oder unvollständig. Überprüfen Sie das Nachrichtenformat, und wiederholen Sie die Anforderung.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MalformedRequest">
      <MemberSignature Language="C#" Value="MalformedRequest" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode MalformedRequest = int32(498)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.MalformedRequest" />
      <MemberSignature Language="VB.NET" Value="MalformedRequest" />
      <MemberSignature Language="F#" Value="MalformedRequest = 498" Usage="Microsoft.Azure.Graphs.GraphStatusCode.MalformedRequest" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>498</MemberValue>
      <Docs>
        <summary>
            Die Anforderungsnachricht wurde nicht ordnungsgemäß formatiert, womit konnte nicht auf allen analysiert werden, oder der Code "Op" wurde nicht erkannt, sodass Gremlin Server es ordnungsgemäß für die Verarbeitung weiterleiten kann. Überprüfen Sie das Nachrichtenformat, und wiederholen Sie die Anforderung.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NoContent">
      <MemberSignature Language="C#" Value="NoContent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode NoContent = int32(204)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.NoContent" />
      <MemberSignature Language="VB.NET" Value="NoContent" />
      <MemberSignature Language="F#" Value="NoContent = 204" Usage="Microsoft.Azure.Graphs.GraphStatusCode.NoContent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>204</MemberValue>
      <Docs>
        <summary>
            Der Server verarbeitet die Anforderung, aber es ist kein Ergebnis zurückgeben (z. B. einen Iterator mit keine Elemente) – keine Nachrichten verbleiben in diesem Datenstrom vorhanden sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialContent">
      <MemberSignature Language="C#" Value="PartialContent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode PartialContent = int32(206)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.PartialContent" />
      <MemberSignature Language="VB.NET" Value="PartialContent" />
      <MemberSignature Language="F#" Value="PartialContent = 206" Usage="Microsoft.Azure.Graphs.GraphStatusCode.PartialContent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>206</MemberValue>
      <Docs>
        <summary>
            Der Server hat einige Inhalte erfolgreich zurückgegeben, aber es gibt weitere im Datenstrom empfangen-warten Sie, bis ein Erfolg, um das Ende des Streams anzugeben.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RateLimiting">
      <MemberSignature Language="C#" Value="RateLimiting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode RateLimiting = int32(429)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.RateLimiting" />
      <MemberSignature Language="VB.NET" Value="RateLimiting" />
      <MemberSignature Language="F#" Value="RateLimiting = 429" Usage="Microsoft.Azure.Graphs.GraphStatusCode.RateLimiting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>429</MemberValue>
      <Docs>
        <summary>
            Berechnen Sie das Kontingent wurde überschritten. (HTTP-Statuscode:)
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ScriptEvaluationError">
      <MemberSignature Language="C#" Value="ScriptEvaluationError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ScriptEvaluationError = int32(597)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ScriptEvaluationError" />
      <MemberSignature Language="VB.NET" Value="ScriptEvaluationError" />
      <MemberSignature Language="F#" Value="ScriptEvaluationError = 597" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ScriptEvaluationError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>597</MemberValue>
      <Docs>
        <summary>
            Das Skript zur Verarbeitung in die ScriptEngine mit Fehlern ausgewertet, und konnte nicht verarbeitet werden. Überprüfen Sie das Skript zur Syntaxfehler oder andere Probleme, und klicken Sie dann erneut.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerError">
      <MemberSignature Language="C#" Value="ServerError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerError = int32(500)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerError" />
      <MemberSignature Language="VB.NET" Value="ServerError" />
      <MemberSignature Language="F#" Value="ServerError = 500" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>500</MemberValue>
      <Docs>
        <summary>
            Ein allgemeiner Serverfehler ist aufgetreten, der verhindert, dass die Anforderung verarbeitet.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerSerializationError">
      <MemberSignature Language="C#" Value="ServerSerializationError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerSerializationError = int32(599)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerSerializationError" />
      <MemberSignature Language="VB.NET" Value="ServerSerializationError" />
      <MemberSignature Language="F#" Value="ServerSerializationError = 599" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerSerializationError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>599</MemberValue>
      <Docs>
        <summary>
            Der Server konnte nicht serialisiert ein Objekt, das die Anforderung aus dem bereitgestellten Skript zurückgegeben wurde. Transformieren Sie das Objekt in etwas Gremlin Server innerhalb des Skripts zu verarbeiten oder Mapper Serialisierungsklassen Gremlin-Server installiert werden kann.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="ServerTimeout" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode ServerTimeout = int32(598)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="ServerTimeout" />
      <MemberSignature Language="F#" Value="ServerTimeout = 598" Usage="Microsoft.Azure.Graphs.GraphStatusCode.ServerTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>598</MemberValue>
      <Docs>
        <summary>
            Der Server eine die Timeouteinstellungen für die Anforderung überschritten und kann daher nur teilweise geantwortet oder überhaupt nicht reagierte.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Success = int32(200)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 200" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>200</MemberValue>
      <Docs>
        <summary>
            Der Server erfolgreich verarbeitet eine Anforderung zum Abschluss des Vorgangs: keine Nachrichten verbleiben in diesem Datenstrom vorhanden sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unauthorized">
      <MemberSignature Language="C#" Value="Unauthorized" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Graphs.GraphStatusCode Unauthorized = int32(401)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Graphs.GraphStatusCode.Unauthorized" />
      <MemberSignature Language="VB.NET" Value="Unauthorized" />
      <MemberSignature Language="F#" Value="Unauthorized = 401" Usage="Microsoft.Azure.Graphs.GraphStatusCode.Unauthorized" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <MemberValue>401</MemberValue>
      <Docs>
        <summary>
            Die Anforderung hat versucht, auf Ressourcen zugreifen, denen der anfordernde Benutzer keinen Zugriff auf.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>