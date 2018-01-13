<Type Name="Receiver&lt;T&gt;" FullName="Microsoft.Azure.Devices.Receiver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class Receiver&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Receiver`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Receiver`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Receiver(Of T)" />
  <TypeSignature Language="F#" Value="type Receiver&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="a2c33-101">Enthält Methoden, die Dienste, zum Ausführen verwenden können von Empfangsvorgänge.</span><span class="sxs-lookup"><span data-stu-id="a2c33-101">Contains methods that services can use to perform receive operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Receiver ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Receiver`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task AbandonAsync (T t);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(!T t) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Receiver`1.AbandonAsync(`0)" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="receiver.AbandonAsync t" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="t" Type="T" />
      </Parameters>
      <Docs>
        <param name="t">To be added.</param>
        <summary>
            <span data-ttu-id="a2c33-102">Setzt eine empfangene Nachricht zurück in die Warteschlange</span><span class="sxs-lookup"><span data-stu-id="a2c33-102">Puts a received message back into the queue</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CompleteAsync (T t);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(!T t) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Receiver`1.CompleteAsync(`0)" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="receiver.CompleteAsync t" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="t" Type="T" />
      </Parameters>
      <Docs>
        <param name="t">To be added.</param>
        <summary>
            <span data-ttu-id="a2c33-103">Löscht eine empfangene Nachricht aus der Warteschlange</span><span class="sxs-lookup"><span data-stu-id="a2c33-103">Deletes a received message from the queue</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;T&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Receiver`1.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReceiveAsync () As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="receiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a2c33-104">Eine Meldung mit der Standard-Timeoutwert.</span><span class="sxs-lookup"><span data-stu-id="a2c33-104">Receive a message using the default timeout.</span></span>
            </summary>
        <returns><span data-ttu-id="a2c33-105">Die empfangsnachricht oder Null, wenn keine Nachricht erst das Standardtimeout aufgetreten</span><span class="sxs-lookup"><span data-stu-id="a2c33-105">The receive message or null if there was no message until the default timeout</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;T&gt; ReceiveAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; ReceiveAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Receiver`1.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReceiveAsync (timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="receiver.ReceiveAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="a2c33-106">Das Timeout für das Empfangen einer Nachricht</span><span class="sxs-lookup"><span data-stu-id="a2c33-106">The timeout for receiving a message</span></span></param>
        <summary>
            <span data-ttu-id="a2c33-107">Empfängt eine Nachricht</span><span class="sxs-lookup"><span data-stu-id="a2c33-107">Receives a message</span></span>
            </summary>
        <returns><span data-ttu-id="a2c33-108">Die empfangsnachricht oder Null, wenn keine Nachricht erst das festgelegte Timeout aufgetreten</span><span class="sxs-lookup"><span data-stu-id="a2c33-108">The receive message or null if there was no message until the specified timeout</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>